## Setup Neovim like an IDE

![Screenshot](https://imgur.com/8gjO3cX)

## Overview

- Terminal: [iTerm2](https://www.iterm2.com/) or [Alacritty](https://github.com/alacritty/alacritty)
- NeoVim: [nvim](https://neovim.io/)
- Shell: [Fish](https://fishshell.com/)
- Terminal Multiplexer: [tmux](https://github.com/tmux/tmux)
- My iTerm2 theme: ``./colors/nmeowt.itermcolors``
- Fish shell framework: [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish)
- My fish theme: [ocean](https://github.com/oh-my-fish/oh-my-fish/blob/master/docs/Themes.md#ocean)

## Installation

1. Backup:
```
cp -rf ~/.config/nvim/ ~/.config/backup.nvim/
```

2. Remove:
```
rm -rf ~/.config/nvim
```

3. Clone:
```
$ git clone https://github.com/nmeowt/nmt-vim-config.git ~/.config/nvim/
```

In `vim/neovim` run:

    :PlugClean

And follow its steps.

After, in `vim/neovim` run:

    :PlugInstall

If you want to get newest version of `vim/neovim` plugin, in `vim/neovim` simply run:

    :PlugUpdate


Credit
-------

Thanks to:

[The Full Snack](https://thefullsnack.com/) and his amazing [config](https://github.com/huytd/vim-config)
