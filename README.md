# Vim 
### Requirements
* Git Bash (if on Windows)
* Vim 7.4

### *nix Setup

1. Clone into ~/yourRepoDirectory/...
2. Remove ~/.vim directory and ~/.vimrc 
3. ln -s ~/yourRepoDirectory/dotfiles/vim ~/.vim 
4. If submodules are empty, call git submodule init && git submodule update

### Windows Setup
1. Clone into ~/yourRepoDirectory/...
<<<<<<< HEAD
2. Remove ~/vimfiles directory and ~/.vimrc 
=======
2. Remove ~/vimfiles directory and ~/\_vimfiles 
>>>>>>> 46fb69b95a3e502a58812eb8c02280b3bb513af3
3. ln -s ~/yourRepoDirectory/dotfiles/vim ~/vimfiles
	1. If permission issues: [read here.] (http://www.dotnetsurfers.com/blog/2013/10/15/using-the-same-vimrc-with-multiple-operating-systems)
4. If submodules are empty, call git submodule init && git submodule update
