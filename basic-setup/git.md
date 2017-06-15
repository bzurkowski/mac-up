Install git:

```bash
brew install git
git --version
```

Setup user name and email in global config:

```bash
git config --global user.name "User Name"
git config --global user.email "user.name@email.com"
```

Generate SSH keys:

```bash
ssh-keygen -t rsa -b 4096 -C "user.name@email.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

Add generated public key \`id\_rsa.pub\` to Github account.

