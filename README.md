# setup
dotfiles etc for configurations and ergonomics 

## vim 
Installing Pathogen as default plugin manager
```bash
mkdir ~/.vim/autoload ~/.vim/bundle
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
<i>For ref:</i>&nbsp;<a href="https://github.com/tpope/vim-pathogen">https://github.com/tpope/vim-pathogen</a>

In `~/.vimrc` make sure the following is included:
```bash
execute pathogen#infect()
```

<hr>

Installing NERDTree
```bash
mkdir ~/.vim/bundle/nerdtree
cd ~/.vim/bundle/nerdtree
git clone https://github.com/scrooloose/nerdtree.git
```
<i>For ref:</i>&nbsp;<a href="https://github.com/scrooloose/nerdtree">https://github.com/scrooloose/nerdtree</a>

<hr>

Installing Color Schemes
```bash
mkdir ~/.vim/bundle/vim-colorschemes
cd ~/.vim/bundle/vim-colorschemes
git clone https://github.com/flazz/vim-colorschemes.git
```
<i>For ref:</i>&nbsp;<a href="https://github.com/flazz/vim-colorschemes">https://github.com/flazz/vim-colorschemes</a>


## makefile
Refer to `man make` for all the information needed to produce good makefiles.
