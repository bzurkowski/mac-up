Install rbenv:

```bash
brew install rbenv ruby-build rbenv-default-gems
echo 'eval "$(rbenv init -)"' >> .zshrc
```

Install global Ruby:

```bash
rbenv install 2.3.1
rbenv global 2.3.1
```

Setup bundler:

```bash
gem install bundler
echo 'bundler' >> "$(brew --prefix rbenv)/default-gems"
echo 'gem: --no-document' >> ~/.gemrc
```



