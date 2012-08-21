## Installation

1. `$ mkdir ~/dotfiles`
2. `$ git clone git@github.com:ravinggenius/dotfiles-vim.git ~/dotfiles/vim`
3. `$ ~/dotfiles/vim/INSTALL`

## Caveats

### Powerline

[Powerline](https://github.com/Lokaltog/vim-powerline) can use a patched font (and is configured to do so) to display some fancy symbols. To take advantage of this, you will need to [patch your font](https://github.com/Lokaltog/vim-powerline/tree/develop/fontpatcher) of choice. Alternatively you may download any of these pre-patched [font](https://github.com/Lokaltog/vim-powerline/wiki/Patched-fonts).

Or you could configure `g:Powerline_symbols` to not be fancy if you do not care.

### vim-open

`:Open` will open a directory relative to `~/Code`. Change `g:project_dir` if you use a different path.
