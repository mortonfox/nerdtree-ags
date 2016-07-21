# nerdtree-ags

## Introduction

ags\_path is a [NERDTree](https://github.com/scrooloose/nerdtree)
plugin that adds a menu item to search for a keyword or regex under the
selected path using [vim-ags](https://github.com/gabesoft/vim-ags).

## Installation

### Pathogen

Use the following commands:

    cd ~/.vim/bundle
    git clone https://github.com/mortonfox/nerdtree-ags.git

### Vundle

Add the following to your vimrc:

    Plugin 'mortonfox/nerdtree-ags'

Install with ```:PluginInstall```.

### Manual Installation

Copy ```ags_path.vim``` to ```~/.vim/nerdtree_plugin/``` (*nix)
or ```~/vimfiles/nerdtree_plugin``` (Windows).

## Usage

In the NERDTree window, select the desired folder and then type ```m```
and ```s```. Enter a keyword or regex at the prompt to get a vim-ags search
results window.
