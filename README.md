# tmux_cheatsheet

## SESSIONS

Start new session:

    tmux  
    tmux new -s session_name  

Kill session:

    tmux kill-session -t session_name

Attach to session:

    tmux a

List all sessions:

    tmux ls

## WINDOWS

Create new window:

    Ctrl+B C

List windows:

    Ctrl+B W

Next window:

    Ctrl+B N

Previous window:

    Ctrl+B P

Kill window:

    Ctrl+B &


Rename window:

    Ctrl+B ,

Find window:

    Ctrl+B F

## PANES

Create vertical split:

    Ctrl+B %

Create horizontal split:

    Ctrl+B "

Toogle pane zoom:

    Ctrl+B Z

Kill pane:

    Ctrl+B X

Resize panes:

    Ctrl+B+arrows

Move to other panes:

    Ctrl+B arrows

Scroll pane:

    Ctrl+B [  +  up arrow / down arrow / page up / page down

Move pane to next pane:

    Ctrl+B }

Move pane to previous pane:

    Ctrl+B {


