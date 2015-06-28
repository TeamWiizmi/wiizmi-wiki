# Homebrew

## Official website

[Homebrew - The missing package manager for OS X](http://brew.sh)

Homebrew is a very important tool for Mac OS.  
To install


## Install

```sh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Usage

### Install command line tools

```sh
brew install wget
```

### Update brew

```sh
brew update
```

### Upgrade installed application

```sh
# upgrade all application
brew upgrade --all

# upgrade a specific application
brew upgrade wget
```

### Clean old application version

```sh
brew cleanup
```
