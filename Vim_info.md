:[000Index](../000Index.md)
# VIM info
#vim
## Questions to be resolved
- Search and replace (find space replace to line break) 
- Can VIM display the image for markdown. (Markdown plugin)

## Movement
`Ctrl+W+W`:::Switch between Vim window splits
<!--SR:!2024-12-14,3,250!2024-12-25,8,250-->
`Ctrl + F`::: Page down, moving Forward
<!--SR:!2024-12-14,2,230!2024-12-14,3,250-->
`Ctrl + B` ::: page up, moving Backward
<!--SR:!2024-12-14,2,230!2024-12-21,5,230-->
`gt` ::: To switch between tabs you can use
<!--SR:!2024-12-14,3,250-->
`Ctrl+ ]` ::: Jump to a subject
`Ctrl + T / O` ::: Jump back to previous position
`#x` ::: Delete \# character
`#dw` ::: Delete \# word
`$`  ::: move to the end of line, INCLUDING the last character.
`d$`  ::: delete to the end of the line
`de /w` ::: delete word
`Ctrl + R` ::: Redo 
`Ctrl + r` ::: Redo 
`N` ::: backward next; previous next
`w` ::: move to begin of next word
<!--SR:!2000-01-01,1,250!2024-12-14,2,246-->
`b` ::: begin of previours word, word begin
 `e` ::: to the end of the current word, word end, INCLUDING the last character.
`^` ::: Go to the beginning of the line and after whitespace.
`0` ::: Go to the beginning of the line
`"+p` :::  to paste from clipboard.
`"*y` :::  to copy to system clipboard.
`qa` ::: begin to record the macro
`q`  ::: stop to record the macro
<!--SR:!2024-12-14,2,246!2024-12-21,5,246-->
`J`  ::: Uppercase J will join that line and the next line

## Command
**Command**|**Usage**
----------|------------
`:ter` ::: Open a terminal / shell inside VIM
`:vertical botright term` ::: Open a terminal vertically at the right side of the window
`:tabnew` ::: You can open a new tab with the command
`:tabnew [filename]` ::: You can open a new tab with the command
`:q<Enter>` ::: Close this window
`:qa!<Enter>` ::: Get out of Vim
<!--SR:!2024-12-13,1,226!2000-01-01,1,250-->
`:reg<Enter>` ::: Show yank register
`:register<Enter>` ::: Show yank register
`:cd mydirectory` ::: Set working / current directory in Vim


## Motion
**Command**|**Usage**
----------|------------
- $ - | to the end of the line, INCLUDING the last character.

## Plugin


## Script

