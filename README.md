#### dotfiles-backup

##### clone repository
```bash
mkdir -p ~/Sites/dotfiles-backup
git clone git@github.com:ngonzalez/dotfiles-backup.git ~/Sites/dotfiles-backup
```

##### install
```bash
ln -s ~/Sites/dotfiles-backup/.zshrc ~/.zshrc
ln -s ~/Sites/dotfiles-backup/.gitconfig ~/.gitconfig
```