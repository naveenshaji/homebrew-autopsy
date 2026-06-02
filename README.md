# Homebrew Autopsy Tap

Homebrew tap for [Autopsy Memory](https://github.com/naveenshaji/autopsy).

## Install

```bash
brew tap naveenshaji/autopsy
brew install autopsy-memory
autopsy version --json
autopsy doctor
```

Start the macOS menu bar utility and keep it visible at login:

```bash
autopsy menubar --install-launch-agent
```

Stop it:

```bash
autopsy menubar --uninstall-launch-agent
```
