# Ruby

##### Install rbenv

```bash
brew install rbenv ruby-build rbenv-default-gems
echo 'eval "$(rbenv init -)"' >> .zshrc
```

##### Setup global Ruby version

```bash
rbenv install 2.3.1
rbenv global 2.3.1
```

##### Setup bundler

```
gem install bundler
```

##### Add bundler to list of default gems installed by rbenv

This will tell rbenv to install bundler each time a new version of Ruby has been installed.

```
echo 'bundler' >> "$(brew --prefix rbenv)/default-gems
```

##### Prevent fetching documentation for each installed gem

```
echo 'gem: --no-document' >> ~/.gemrc
```



