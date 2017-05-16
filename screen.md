# Screen
Screen is a full-screen window manager that multiplexes a physical terminal between several processes.

# Commands

Command | Description
-|-
$ screen -S <name> | Start session with name
$ screen -ls | List running sessions
$ screen -x | Attach to running sessions
$ screen -r <name> | Attach to running sessions with name


## Window management

Shortcut | Description
-|-
ctrl+a c | Create new window
ctrl+a n | Next window
ctrl+a p | Previous window
ctrl+a " | Window list
ctrl+a d | Detach
ctrl+a D D | Detach and exit
ctrl+a A | Rename current window

## Split Screen

Shortcut | Description
-|-
ctrl+a S | Split horizontally
ctrl+a V | Split vertically
ctrl+a tab | Next display region
ctrl+a X | Remove current region
ctrl+q Q | Remove all regions


## Others

Shortcut | Description
-|-
ctrl+a esc | Copy mode
ctrl+a ] | Paste
