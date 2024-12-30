:[000Index](../000Index.md)
# VIM info
#vim
## Questions to be resolved
- Search and replace (find space replace to line break) 
- Can VIM display the image for markdown. (Markdown plugin)

## Movement
`Ctrl+W+W`:::Switch between Vim window splits
<!--SR:!2025-01-06,8,250!2025-01-18,20,250-->
`Ctrl + F`::: Page down, moving Forward
<!--SR:!2025-01-03,5,230!2025-01-05,7,250-->
`Ctrl + B` ::: page up, moving Backward
<!--SR:!2024-12-30,1,210!2025-01-01,3,210-->
`gt` ::: To switch between tabs you can use
<!--SR:!2025-01-07,9,250!2024-12-31,2,242-->
`Ctrl+ ]` ::: Jump to a subject
`Ctrl + T / O` ::: Jump back to previous position
`#x` ::: Delete \# character
<!--SR:!2024-12-30,1,225!2000-01-01,1,250-->
`#dw` ::: Delete \# word
`$`  ::: move to the end of line, INCLUDING the last character.
`d$`  ::: delete to the end of the line
`de /w` ::: delete word
`Ctrl + R` ::: Redo 
`Ctrl + r` ::: Redo 
`N` ::: backward next; previous next
`w` ::: move to begin of next word
<!--SR:!2024-12-31,2,245!2025-01-03,5,246-->
`b` ::: begin of previours word, word begin
 `e` ::: to the end of the current word, word end, INCLUDING the last character.
`^` ::: Go to the beginning of the line and after whitespace.
`0` ::: Go to the beginning of the line
`"+p` :::  to paste from clipboard.
`"*y` :::  to copy to system clipboard.
`qa` ::: begin to record the macro
`q`  ::: stop to record the macro
<!--SR:!2025-01-03,5,246!2025-01-10,12,246-->
`J`  ::: Uppercase J will join that line and the next line

## Command
**Command**|**Usage**
----------|------------
`:ter` ::: Open a terminal / shell inside VIM
<!--SR:!2024-12-31,2,242!2000-01-01,1,250-->
`:vertical botright term` ::: Open a terminal vertically at the right side of the window
`:tabnew` ::: You can open a new tab with the command
`:tabnew [filename]` ::: You can open a new tab with the command
`:q<Enter>` ::: Close this window
`:qa!<Enter>` ::: Get out of Vim
<!--SR:!2024-12-31,2,226!2024-12-31,2,245-->
`:reg<Enter>` ::: Show yank register
<!--SR:!2000-01-01,1,250!2024-12-30,1,222-->
`:register<Enter>` ::: Show yank register
`:cd mydirectory` ::: Set working / current directory in Vim


## Motion
**Command**|**Usage**
----------|------------
- $ - | to the end of the line, INCLUDING the last character.

## Plugin


## Script

