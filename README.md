# vimrc
This is a .vimrc file that implements suggestions from a few vim articles and
blog entries.

It disables the arrow keys in insert mode to force returning to normal mode
for movement.

It also adds `jj`, `jk`, and `kj` as keystroke alternatives to the escape key
to allow faster switching to normal mode.` 

It displays relative line numbers while in normal or visual mode so that the user can
know at a glance how far they should jump relative to their current position. 

Move quickly up or down to the precise location by using j and k preceeded with
the relative number.

eg. You are on line number 551, and you need to jump to line 557. Using absolute
line numbers, you would have to type `557 G` to jump there. Alternatively, `6j`
to jump down six lines from the cursor position, but you would first have to do
the math to know the number to jump. This is where relative line numbering
becomes handy, because it tells you immediately the number you can use.

The script also toggles to absolute line numbers while in insert mode since
movement is disabled in that mode.


