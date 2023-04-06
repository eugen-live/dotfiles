# dotfiles
## mac os
```console
ln -s ~/dotfiles/.vim/vimrc ~/.vim/vimrc
```
```console
ln -s ~/dotfiles/nvim/init.vim ~/.config/nvim/init.vim
```

## windows
```console
mkdir %userprofile%\.vim && mklink %userprofile%\.vim\vimrc %userprofile%\dotfiles\.vim\vimrc
```

```console
mkdir %userprofile%\.config\nvim\ && mklink %userprofile%\.config\nvim\init.vim %userprofile%\dotfiles\nvim\init.vim
```
