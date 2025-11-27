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

## Install nvm
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/HEAD/install.sh | bash
```

## Install bun
```bash
curl -fsSL https://bun.sh/install | bash
```

## Install brew packages

```bash
xargs brew install < brew-apps.txt
```

## NPM global packages

```bash
xargs npm install -g < npm-deps.txt
```

messenger appstore version: `Version 520.0.0 (777169672)`