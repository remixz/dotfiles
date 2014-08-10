## dotfiles

### setup

```bash
curl -L https://github.com/bpinto/oh-my-fish/raw/master/tools/install.fish | fish
cat fish.config > ~/.config/fish/config.fish
cat fish_prompt.fish > ~/.oh-my-fish/themes/robbyrussell/fish_prompt.fish
gi osx node > ~/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
```