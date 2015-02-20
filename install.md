<!-- first copy vim folder to ~/.vim -->
ln -sFi ~/Projects/Dotfiles/vim ~/.vim

<!-- copy ~/Projects/Dotfiles/vim/vimrc to ~/.vimrc -->
ln -sFi ~/Projects/Dotfiles/vim/vimrc ~/.vimrc

<!-- make temp folders -->
mkdir ~/.vim/backups
mkdir ~/.vim/swaps
mkdir ~/.vim/undo

<!-- copy ~/Projects/Dotfiles/zsh/zshrc to ~/.zshrc -->
ln -sFi ~/Projects/Dotfiles/zsh/zshrc ~/.zshrc