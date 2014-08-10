## dotfiles

### setup

```bash
curl -L https://github.com/bpinto/oh-my-fish/raw/master/tools/install.fish | fish
cat config.fish > ~/.config/fish/config.fish
cat fish_prompt.fish > ~/.oh-my-fish/themes/robbyrussell/fish_prompt.fish
gi osx node > ~/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
```

### notes

to ensure compatiblity with things expecting bourne-style shells, my default shell is `bash`, and then i set the login command in iterm to `/usr/local/bin/fish --login`