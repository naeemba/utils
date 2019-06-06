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
