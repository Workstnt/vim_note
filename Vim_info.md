[000Index](../000Index.md)
# VIM Learning note
#vim
## Table of Contents
- [Questions](\#questions)
- [Introduction](\#introduction)
- [Modes](\#modes)
- [Movement](\#movement)
- [Command](\#command)
- [Plugin](\#plugin)
- [Script](\#script)
- [Customization](\#customization)
- [Flow sample](\#flow-sample)
- [Practice](\#practice)

## Questions

## Introduction
VIM is a powerful text editor with modal functionality, designed for efficient text editing. This document will serve as a personal guide to mastering VIM step by step and future reference.
Reference: [[assets/Vim_info/Vim实用技巧（第2版）.pdf]]
## Modes
- `Esc` ::: Key to access to **Normal Mode**
- `i` ::: Key to access to **Insert Mode**
- `v` ::: Key to access to **Visual Mode**
- `:` ::: Key to access to **Command Mode**

## Movement
All commands in this section should be press in normal mode.

### Exiting
- `ZZ` ::: Save and quit
- `ZQ` ::: Quit without checking changes
<!--SR:!2000-01-01,1,250!2024-12-31,1,222-->
### Misc
- `Ctrl+W+W`:::Switch between Vim window splits 
<!--SR:!2025-01-06,8,250!2025-01-18,20,250-->
- `Ctrl + F`::: Page down, moving Forward
<!--SR:!2025-01-03,5,230!2025-01-05,7,250-->
- `Ctrl + B` ::: page up, moving Backward
<!--SR:!2025-01-01,2,210!2025-01-01,3,210-->
- `gt` ::: To switch between tabs you can use
<!--SR:!2025-01-07,9,250!2000-01-01,1,250-->
- `Ctrl+ ]` ::: Jump to a subject
- `Ctrl + T / O` ::: Jump back to previous position
- `#x` ::: Delete \# character
<!--SR:!2024-12-31,1,205!2000-01-01,1,250-->
- `#dw` ::: Delete \# word
- `$`  ::: move to the end of line, INCLUDING the last character.
<!--SR:!2025-01-01,2,242!2000-01-01,1,250-->
- `d$`  ::: delete to the end of the line
<!--SR:!2000-01-01,1,250!2025-01-01,2,242-->
- `de /w` ::: delete word
<!--SR:!2024-12-31,1,222!2000-01-01,1,250-->
- `Ctrl + R` ::: Redo
<!--SR:!2000-01-01,1,250!2024-12-31,1,222-->
- `Ctrl + r` ::: Redo 
- `N` ::: backward next; previous next
<!--SR:!2000-01-01,1,250!2025-01-01,2,242-->
- `w` ::: move to begin of next word
<!--SR:!2024-12-31,2,245!2025-01-03,5,246-->
- `b` ::: begin of previours word, word begin
-  `e` ::: to the end of the current word, word end, INCLUDING the last character.
<!--SR:!2000-01-01,1,250!2025-01-01,2,242-->
- `^` ::: Go to the beginning of the line and after whitespace.
- `0` ::: Go to the beginning of the line
<!--SR:!2000-01-01,1,250!2025-01-01,2,242-->
- `"+p` :::  to paste from clipboard.
<!--SR:!2000-01-01,1,250!2024-12-31,1,222-->
- `"*y` :::  to copy to system clipboard.
- `qa` ::: begin to record the macro
- `q`  ::: stop to record the macro
<!--SR:!2025-01-03,5,246!2025-01-10,12,246-->
- `J`  ::: Uppercase J will join that line and the next line

## Command
### Search & Replace
- `:s/\s/\r/g` ::: Find space replace with line break

### Misc
- `:ter` ::: Open a terminal / shell inside VIM
<!--SR:!2025-01-01,2,242!2025-01-01,2,242-->
- `:vertical botright term` ::: Open a terminal vertically at the right side of the window
<!--SR:!2025-01-01,2,242!2024-12-31,1,222-->
- `:tabnew` ::: You can open a new tab with the command. Practice[^1]
- `:tabnew [filename]` ::: You can open a new tab with the command
<!--SR:!2000-01-01,1,250!2024-12-31,1,222-->
- `:q<Enter>` ::: Close this window
- `:qa!<Enter>` ::: Get out of Vim
<!--SR:!2024-12-31,2,226!2024-12-31,2,245-->
- `:reg<Enter>` ::: Show yank register
- `:register<Enter>` ::: Show yank register
<!--SR:!2024-12-31,1,222!2000-01-01,1,250-->
- `:cd mydirectory` ::: Set working / current directory in Vim
- `:ter` ::: Open a terminal / shell inside VIM
<!--SR:!2024-12-31,2,242!2000-01-01,1,250-->
- `:vertical botright term` ::: Open a terminal vertically at the right side of the window
- `:tabnew` ::: You can open a new tab with the command
- `:tabnew [filename]` ::: You can open a new tab with the command
- `:q<Enter>` ::: Close this window
- `:qa!<Enter>` ::: Get out of Vim
<!--SR:!2024-12-31,2,226!2024-12-31,2,245-->
- `:reg<Enter>` ::: Show yank register
<!--SR:!2000-01-01,1,250!2024-12-30,1,222-->
- `:register<Enter>` ::: Show yank register
- `:cd mydirectory` ::: Set working / current directory in Vim


## Plugin

## Script


## Customization

## Flow-sample
```mermaid
flowchart TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
```
![[assets/Vim_info/image-20250103201126895.png]]


## Practice
[^1]: Open abc.txt in a new tab: `:tabnew abc.txt`
