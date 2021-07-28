# macosinstallationscript

Do not install xcode from the script. Use this instead:

```
xcode-select --install
```

What I use to setup macos right from a fresh install

# install homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# install the packages that I use

```
brew install bpytop git
```

# install all the apps

```
brew install --cask \
google-chrome 1password adobe-creative-cloud iterm2 appcleaner atom discord exodus expressvpn ledger-live pock skype spotify transmission zoom
```
