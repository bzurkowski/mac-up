# Package management

## Homebrew

"Must have" package management system that simplifies the installation of software on Apple's macOS operating system.

### Setup

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Usage

##### Find package

```bash
brew search htop
```

##### Install package

```
brew install htop
```

##### Uninstall package

```bash
brew uninstall htop
```

##### Display detailed info about package

```
brew info htop
```

##### Detect potential problems

```bash
brew doctor
```

## Cask

Cask extends Homebrew and brings its elegance, simplicity, and speed to the installation and management of GUI macOS applications such as Google Chrome.

```bash
brew cask
```

### Usage

##### Find application

```
$ brew cask search chrome
google-chrome
```

##### Install application

```bash
$ brew cask install google-chrome
==> Downloading https://dl.google.com/chrome/mac/stable/GGRO/googlechrome.dmg
==> Moving App 'Google Chrome.app' to '/Applications/Google Chrome.app'
🍺  google-chrome was successfully installed!
```



