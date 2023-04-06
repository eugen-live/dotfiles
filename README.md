# dotfiles
## mac os
```console
mkdir -p ~/.vim && ln -s ~/dotfiles/vim/vimrc ~/.vim/vimrc
```
```console
mkdir -p ~/.config/nvim && ln -s ~/dotfiles/nvim/init.vim ~/.config/nvim/init.vim
```

## windows
```console
if not exist %userprofile%\.vim mkdir %userprofile%\.vim && mklink %userprofile%\vim\vimrc %userprofile%\dotfiles\.vim\vimrc
```

```console
if not exist %userprofile%\.config\nvim\ mkdir %userprofile%\.config\nvim\ && mklink %userprofile%\.config\nvim\init.vim %userprofile%\dotfiles\nvim\init.vim
```
