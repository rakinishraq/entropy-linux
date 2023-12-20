# entropy-linux
My linux dotfiles

## Experimental dotfiles management
```bash
alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
dotfiles config --local status.showUntrackedFiles no

dotfiles add .vimrc  
dotfiles commit -m "Add .vimrc"  
dotfiles push`
