# raspberry-setup

## Install GIT
`sudo apt install git-all`

## Install ZSH
1. Connect to your raspberry Pi with SSH
2. Install zsh : `sudo apt-get update && sudo apt-get install zsh`
3. Edit your passwd configuration file to tell which shell to use for user `pi` : `sudo vim /etc/passwd` and change 
`/bin/bash` and `/bin/zsh`
4. Reconnect to your raspberry, and check that zsh is the shell with `echo $0`.
5. Switch to root : `sudo su`
6. Install OhMyZsh : `sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"`
7. Disconnect from your instance and reconnect it. 


## Install VIM
`sudo apt-get update && sudo apt-get install vim`

`git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime`

`sh ~/.vim_runtime/install_awesome_vimrc.sh`

## Configure SSH

