# filebeat-formula
[![Build Status](https://travis-ci.org/ssplatt/filebeat-formula.svg?branch=master)](https://travis-ci.org/ssplatt/filebeat-formula)

Install and configure filebeat

## How to use test-kitchen on MacOSX

Install and setup brew:
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Install vagrant with brew:
```
brew install cask
brew cask install vagrant
```

Install test-kitchen:
```
sudo gem install test-kitchen
sudo gem install kitchen-vagrant
sudo gem install kitchen-salt
```

Run a converge on the default configuration:
```
kitchen converge default
```
