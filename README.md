# VIM

Vim is a modal editor. Meaning it has modes.

. - repeat action

u - undo action

## ESC - COMMAND mode:

## v - enter visual mode

y - yank(copy)
c - cut
p - paste

### :<LINENUMBER> - go to line
:75 - go to line 75
 
### :q - quit
:q! - quit without saving

### p - paste
(copy + paste) - dd (delte line) + p (paste)

### d - delete

SHIFT + D - delte from cursor until end of line

d+w - delete word

dd - delete a line

8dd - delete 8 lines

diw - delete inner word

das - delete a sentence

dit - delete inner tag

di{ - delete inner parenthesis

di( - delete inner brackets

dip - delete inner paragraph

AROUND

dap - delete AROUND paragraph

### c - change
cf<character> - change until <character>

### f - forward/find
f<character> - find next character
F<character> find previous character

### j/k - move
j - move cursor down
k - move cursor up
h - move cursor left
l - move cursor right

5j - move 5 lines down
 
### / - search
/<searchString> - go to <searchString>
 n - next result
 SHIFTn - previous result

### replace
 :s%/searchString/replaceString

## i - INSERT mode
ESC - EXIT insert mode


## spilt screens
:sp - open horizontal split
:vs - open vertical split

:SPACEq - close slit

# VIM on a Macbook with Touchbar
https://csswizardry.com/2017/01/preparing-vim-for-apples-touch-bar/#fn:1
