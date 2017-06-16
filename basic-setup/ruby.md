# Ruby

##### Install rbenv

```bash
brew install rbenv
echo 'eval "$(rbenv init -)"' >> .zshrc
```

##### Install ruby-build

ruby-build is an rbenv plugin that provides an rbenv install command to compile and install different versions of Ruby on UNIX-like systems.

```bash
brew install ruby-build
```

##### Install rbenv-default-gems

The plugin hooks into the rbenv install command to automatically install predefined gems every time you install a new version of Ruby.

```bash
brew install rbenv-default-gems
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

##### Setup global Ruby version

```bash
rbenv install 2.3.1
rbenv global 2.3.1
```



