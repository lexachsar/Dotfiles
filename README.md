# Description

# StartWithUbuntuScript.sh

Just a script to install needed software.

## Includes:

1. Telegram;
2. Spotify;
3. SSH;
4. Firefox flash player (pepperflash);
5. Chromium-browser;
6. Unetbootin;
7. Intellij Idea (community edition);
8. Octave;
9. Russian language package for libreoffice;
10. Vim;
11. GNU C++ compiler;
12. Tmux;
13. Nmap;
14. Git;
15. TrueCrypt;
16. CryptSetup;
17. Workflowy.

# tmux

Includes config file [.tmux.conf](tmux/config/.tmux.conf)

## Changes in [.tmux.conf](tmux/config/.tmux.conf)


1. Default terminal -- gnome-terminal;
2. Default shell -- /bin/zsh;
3. Default history limit -- 2000;
4. New windows and pane split's on current directory;
5. Split panes using h and v (i3wm binding);
6. Enabled mouse mode;
7. Enabled mouse scroll

# [vim](https://www.vim.org/)

Includes config file [.vimrc](/vim/config/.vimrc)

## Sources
1. [How To Vimrc](https://dougblack.io/words/a-good-vimrc.html)
2. [Vim 02 -- Конфигурация и плагины](https://www.youtube.com/watch?v=VPENostK_3w)
3. [Vim 03 -- Vim 03 - Плагины. Самое необходимое](https://www.youtube.com/watch?v=pIcLJc85RDc)
4. [The Ultimate Vimrc](https://github.com/amix/vimrc/blob/master/vimrcs/basic.vim)

## Changes in [.vimrc](/vim/config/.vimrc)

1. UI Layout
- Vim shows current command in bottom bar
- Vim highlight current line
- Graphical menu of all the matches you can cycle through.
- Highlight matching [{()}]
2. Searching
- Vim history is set to 500 lines
- Ignore case when searching
- Highlight search results
- Highlight choosen search result
- For regular expressions turned magic on
3. Tmux
- Allows cursor change in tmux mode
4. Backups
- Vim moves .swp files into /tmp directory, so they doesn't annoy
5. Installed plugins
- [Nerd tree](https://github.com/scrooloose/nerdtree)
- [You Complete Me](https://github.com/Valloric/YouCompleteMe)
- [Auto pairs](https://github.com/jiangmiao/auto-pairs)
- [Ctrlp](https://github.com/kien/ctrlp.vim) for file search
- [Vimtex](https://github.com/lervag/vimtex) for latex files
- [Undo Tree](https://github.com/mbbill/undotree)
- [Syntastic](https://github.com/scrooloose/syntastic) for errors highlight
- [Vim-Airline](https://github.com/vim-airline/vim-airline) Lean & mean status/tabline for vim that's light as air

6. Key mappings
- Ctrl+e -- Nerd Tree toggle
- Ctrl+u -- Undo Tree toggle

7. Extra
- Set to auto read when a file is changed from the outside

# [TLP](https://wiki.archlinux.org/index.php/TLP)

## Sources
1. [TLP - Configuration](http://linrunner.de/en/tlp/docs/tlp-configuration.html)
