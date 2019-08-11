# VIM Commands

|Command|Description|Source|Details|
|-------|-----------|------|-------|
|`=i{`|Correct indentions|[source](https://www.freecodecamp.org/news/learn-linux-vim-basic-features-19134461ab85/)|Place the cursor anywhere within a block you want to indent, press Esc to enter normal mode and then: =i{|
|`m{lowercaseletter}`|Create local bookmark|[source](https://www.freecodecamp.org/news/learn-linux-vim-basic-features-19134461ab85/)||
|`:marks`|List all local bookmarks|[source](https://www.freecodecamp.org/news/learn-linux-vim-basic-features-19134461ab85/)||
|`` `{lowercaseletter} ``| Go to bookmark|[source](https://www.freecodecamp.org/news/learn-linux-vim-basic-features-19134461ab85/)||
|`ytx`|Yank till character|[source](https://vim.fandom.com/wiki/Copy,_cut_and_paste)|yank from the current cursor position up to and before the character (til x)|
|`yfx`|Yank till character|[source](https://vim.fandom.com/wiki/Copy,_cut_and_paste)|yank from the current cursor position up to and including the character (find x)|
|`:e %:h/filename`<br />`:w`|Create a new file|[source](https://stackoverflow.com/a/13239757/2443849)|will create a new file named filename in the same directory as the currently open file, and write it|
|`2dt{character}`|Delete until second occurance of `{character}`|[source](https://askubuntu.com/a/64840)|This will delete upto but not including `{character}`|
|`2ft{character}`|Delete until second occurance of `{character}`|[source](https://askubuntu.com/a/64840)|This will delete upto and including `{character}`|
|`daw`|Delete the word under the cursor|[source](https://stackoverflow.com/a/835016/2443849)|Delete a word|
|`caw`|Delete the word under the cursor and put you in insert mode|[source](https://stackoverflow.com/a/835016/2443849)|Change a word|
|`:E`|Open current directories files to select from|[source](https://stackoverflow.com/questions/573039/shortcut-to-open-file-in-vim#comment3399452_574537)|Browsable current directory|
|`:ex`|File explorer|[source](https://stackoverflow.com/a/1205382/2443849)|Open file explorer, hitting `r` on a file will rename it and hitting `d` will delete that file|
|`Gmove {newName}`|Rename file|[source](https://stackoverflow.com/a/13501814/2443849)|Rename current file in buffer, git and disk with undo history|
|`Gwrite`|Add to git|[source](https://stackoverflow.com/a/13501814/2443849)|Add current file to git|
