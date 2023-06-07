# dotfiles
Personal dotfiles

Steps to boostrap on a Mac
1. Install Apples Command Line Tool

xcode-select --install

2. clone repo into new hidden directory

#use SSH or HTTPS, switching remotes later
git clone git@github.com:ThePearPoet143/dotfiles.git
git clone https://github.com/ThePearPoet143/dotfiles.git

3. Create symlinks in Home directory to the real files in the repo

ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.gitconfig ~/gitconfig
ln -s ~/,dotfiles/.oh-my-zsh ~/.oh-my-zsh
ln -s ~/.dotfiles/.powerlevel10k ~/.powerlevel10k


4. Install homebrew

5. To Be Continued....