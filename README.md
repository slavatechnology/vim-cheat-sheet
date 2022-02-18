# vim-cheat-sheet
Hot keys and usefull commands for Vim editor

# SPLITS
:Vex

:Sex

:sp filename	Open filename in horizontal split

:vsp filename	Open filename in vertical split

Ctrl-w h Ctrl-w ←	Shift focus to split on left of current

Ctrl-w l Ctrl-w →	Shift focus to split on right of current

Ctrl-w j Ctrl-w ↓	Shift focus to split below the current

Ctrl-w k Ctrl-w ↑	Shift focus to split above the current

Press Control+w, then hit q to close each window at a time.

CTRL+w, o - close all except current

# SEARCH
You can also search for a whole word by moving the cursor to the word and pressing * (asterisk) to search forwards or # (hash) to search backwards. To find the next match press * or # again.
1. Press /.
2. Type the search pattern.
3. Press Enter to perform the search.
4. Press n to find the next occurrence or N to find the previous occurrence.

https://dev.to/iggredible/how-to-search-and-open-files-in-vim-without-plugins-d52

# TEXT Editing
1. Delete line
2. Press the Esc key to go to normal mode.
3. Place the cursor on the line you want to delete.
4. Type dd and hit Enter to remove the line.
    
# TABS
Ctrl-W c  - to close the current window

:tabe {file}   edit specified file in a new tab

:tabf {file}   open a new tab with filename given, searching the 'path' to find it

gt            go to next tab

gT            go to previous tab

Ctrl-PgDn     go to next tab

Ctrl-PgUp     go to previous tab

# COPY PASTE
1. Press v to select characters
2. Move the cursor to the end of what you want to cut.
3. Press d to cut (or y to copy).
4. Move to where you would like to paste.
5. Press P to paste before the cursor, or p to paste after.

# SEARCH AND REPLACE
`:%s/foo/bar/g` - 
Find each occurrence of 'foo' (in all lines), and replace it with 'bar'.

`:%s/foo/bar/gc` - 
Change each 'foo' to 'bar', but ask for confirmation first.

# INSTALL
sudo apt install vim

sudo apt-get remove --auto-remove vim

vim --version
