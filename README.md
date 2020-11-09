
##### install dependencies
```bash
# install brew https://brew.sh
brew install ffmpeg
```

##### clone repository
```bash
mkdir -p ~/Sites/dotfiles-backup
git clone git@github.com:ngonzalez/dotfiles-backup.git ~/Sites/dotfiles-backup
```

##### install extract tools
```bash
typeset -U PATH path
path=( ~/Sites/dotfiles-backup/tools $path )
```

##### from command line
```bash
$ catcue <DIRECTORY>
$ catm3u <DIRECTORY>
$ convertaiff <DIRECTORY>
$ setdate <DIRECTORY>
```
