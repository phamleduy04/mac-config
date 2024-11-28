# Extra config

## Touch ID authenticate sudo
- https://apple.stackexchange.com/questions/259093/can-touch-id-on-mac-authenticate-sudo-in-terminal


## Install xcode-select

```bash
xcode-select --install
```

## Install brew.sh

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install brew packages

```bash
nano brew-apps.txt

# add packages to brew-apps.txt

xargs brew install < brew-apps.txt
```

## NPM global packages

```bash
xargs npm install -g < npm-deps.txt
```