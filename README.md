# Lazyvim101: [Preparing cheatsheet ...]

Organized by tasks, A quick cheatsheet guide with essential lazyvim shortcuts to make you ready to go.
```
leader = space, means leader is space
```

## Lazy Modes
```
:            → Command mode
Esc          → Normal mode. To navigate/command
i            → Insert mode. To write text/code
v            → Visual mode. To select text
Sft+v        → Visual Line mode. To select line
Ctrl+v       → Visual Block mode. To slect in block or column
a            → Insert mode after cursor
o            → Insert mode on new line below  
```
## File Explorer
```
leader-e   →  Open New tree explorer
```
```
l                    → Open file, Expand/collapse Dir
a                    → Create file/directory
d                    → Delete
r                    → Rename
H                    → Toggle hidden files
q                    → Close explorer
k, j                 → Move up / down in neo tree
h                    → Go to parent directory
?                    → Show Neo-tree keymaps
/                    → Filter/search files
```

## Terminal
```
leader-ft            → Terminal
leader-fT            → Terminal (current directory)
Ctrl+/               → Toggle terminal
Ctrl+\ Ctrl+n        → Exit terminal mode
```

## Files and buffer
```
leader-space         → Find/Open file
leader-bd            → Close file/buffer
Shift+h/l            → Previous/next buffer
leader-,             → List open buffers
leader-bb            → Go to privous opend file/buffer
leader-bo            → Close other file/buffer

```

## Window navigation
```
Ctrl + h             → Toggle between file explorer and buffer window
Ctrl + j             → Buffer window to terminal(if opened)
Ctrl + j,k,l,h       → Move among windows (split windows)
Ctrl + /             → Move to Terminal
```

## Cursor movement
```
h/j/k/l              → Left, down, up, right
w                    → Next word
b                    → Previous word
0                    → Beggining of line
$                    → End of line
gg                   → Top of file
G                    → Bottom of file
Ctrl + d             → Half page down
Ctrl + u             → Half page up
Ctrl + f             → Full page down
Ctrl + b             → Full page up
%                    → Matching bracket
```

## Editing
**[INSERT]**
```
i, a                 → Insert before, after cursor
I, A                 → Insert beginning, end of line
o, 0                 → New line below, above
```
**[DELETE]**
```
x                    → Delete character
dd                   → Delete line
dw                   → Delete word
D                    → Delete to end of line
cc                   → Change entire line
cw                   → Change word
C                    → Change to end of line
```
**[COPY/DO]**
```
y                    → Copy
d                    → Delete
yy                   → Copy line
yw                   → Copy word
p                    → Paste after
P                    → Paste before

u                    → Undo
Ctrl +               → Redo
.                    → Repeat change
```