
### Install homebrew

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Install iterm2

install iterm2 app
```
brew install --cask iterm2
```

install zsh
```
brew install zsh
```

install oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

decorate
```
$ cd Downloads
$ curl -O https://raw.githubusercontent.com/MartinSeeler/iterm2-material-design/master/material-design-colors.itermcolors
```

----------------

## Install flipper

```sh
brew install --cask flipper
```

#### install idb

```
brew tap facebook/fb
brew install idb-companion
pip3 install fb-idb --user
/Users/user_name/Library/Python/3.9/bin/idb
```

#### ANDROID SDK PATH
```sh
brew install --cask zulu11
/Users/user_name/Library/Android/sdk
```

----------------

# __Install cocoapods__
##### Make sure you have Rosetta installed.
This is going to eventually not be a requirement, but I’d give it another couple of years before that’s realistically the case. softwareupdate --install-rosetta


##### Install homebrew.
While there are ways around this, I think that it’s in every developer’s interest to have the brew magic in their toolkit

##### Finally, get your Cocoapods!

Just in case you did a mess before, uninstall whatever you did previously by running sudo __gem uninstall cocoapods__ and then __brew install cocoapods__.


