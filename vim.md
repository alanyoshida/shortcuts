# Vim Shortcuts

## Window manipulation

Shortcut | Description
-|-
ctrl+w s | Split windows
ctrl+w w | switch between windows
ctrl+w q | Quit a window
ctrl+w v | Split windows vertically
ctrl+w t | Go to window topleft
ctrl+w t ctrl-w K | Two vertical to horizontal
ctrl+w t ctrl-w H | Two horizontal to vertical
ctrl+w + | Increase Height (can use multiplier like: `ctrl+w 10 +`)
ctrl+w - | Decrease Height (can use multi)
ctrl+w < | Increase Width (can use multi)
ctrl+w > | Decrease Width (can use multi)
:new | New empty window split horizontally
:vnew | New empty window split vertically

## Tabs

Shortcut | Description
-|-
:tabnew | Create new tab
:tabclose | Close current tab
:tabs | List tabs
:tabn | Go to next tab
:tabp | Go to previous tab
:tabfirt | Go to first tab
:tablast | Go to last tab
:tabonly | Closes other tabs

In normal mode:

Shortcut | Description
-|-
gt | Next tab
gT | Previous tab
{i}gt | Go to tab position

## Search

Shortcut | Description
-|-
:noh | Clear search highlight
/pattern | search for pattern
?pattern | search backward for pattern
n | repeat search in same direction
N | repeat search in opposite direction
:%s/old/new/g | replace all old with new throughout file
:%s/old/new/gc | replace all old with new throughout file with confirmations
ctrl+v (select text) * (for next) # (for previous)  | use n for next, N for Previous

## Moving

Shortcut | Description
-|-
shitf+g | Go to end of file
gg | Go to begining of file
0 | Go to begining of line
$ | Go to end of line
e | Go to end of word
b | Go to beggining of word
^ | Go to first character of line

## Multiple Line Editing

1. `/search`
* `cgn`
 - `.` (n times to change)
 - `n` (if you dont want to change)
* `ctrl+v` (do your selection) then:
 - `shift+i` (for insert mode)
 - `shift+a` (for append mode)
 - `s` (cut)
 - `c` (change mode)
* then `ESC` for apply

## Commands from shell

Shortcut | Description
-|-
:! command %     | Execute command from shell, % being the file name
:r ! ls -ls /home    | Get the output and send to vim
