# Install xcode-select

```bash
xcode-select --install
```

# Install brew.sh

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# Install brew packages

```bash
nano brew-apps.txt

# add packages to brew-apps.txt

xargs brew-apps.txt | xargs brew install
```

# Install