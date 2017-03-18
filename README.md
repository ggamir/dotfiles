#dotfiles#
Just my dotfiles.

##vimrc##

The .vimrc file implements a few suggestions that I found around online.

It disables the arrow keys in insert mode to force returning to normal mode
for movement.

It also adds `jj`, `jk`, and `kj` as keystroke alternatives to the escape key
to allow switching to normal mode without leaving the comfort of your own homekeys.` 

It displays relative line numbers while in normal or visual mode so that the user can
know at a glance how far they should jump relative to their current position. 

Move quickly up or down to the precise location by using j and k preceeded with
the relative number.

eg. You are on line number 551, and you need to jump to line 557. Using absolute
line numbers, you would have to type `557 G` to jump there. Alternatively, `6j`
to jump down six lines from the cursor position, but you would first have to do
the math to know the number to jump. Relative line numbering does the math for
you. More action per keystroke.

The script also toggles to absolute line numbers while in insert mode since
movement this .vimrc disables movment in insert mode.


