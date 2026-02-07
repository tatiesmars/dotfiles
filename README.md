# dotfiles

My config for macOS.

## Refresh snapshots

Run from the repo root:

```bash
# Refresh Homebrew packages
brew bundle dump --file=homebrew/Brewfile --force

# Refresh shell/git configs
cp ~/.zshrc zsh/.zshrc
cp ~/.zprofile zsh/.zprofile


git status
```
