# Steps
## Forked from Astro.Nvim, add support for Tabnine

### Step1: Install Astro.Nvim
```
git clone https://github.com/YesDrX/AstroNvim ~/.config/nvim
nvim +PackerSync
```

### Step2: Install vim-plug
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

### Step3: Complete
```
:PlugInstall
:LspInstall pyright
:TSInstall python
:PackerClean
:PackerSync
```


