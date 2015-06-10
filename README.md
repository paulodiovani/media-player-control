# media-player-control

A (not so) simple bash script to control running players in preferred order

## Install

    # Clone the repos
    git clone https://github.com/paulodiovani/media-player-control.git
    
    # Copy scrip to your PATH
    cp media-player-control/bin/playerctl ~/bin/
    
    # or, alternatively, create a symlink to keep up to date
    cd ~/bin
    ln -s [path-to-media-player-control]/bin/playerctl .
    
## Usage

The script was created to use on hotkeys for your desktop manager, terminal, etc.

Just create the hotkeys for the desired command from bellow. It will do the action
for the first runnint media player from the supported list.

    playerctl [ play | pause | toggle | stop | prev | next ]

## Supported media players

- Audacious
- Exaile
- Spotify (Linux client)
- MPD -- _Music player daemon_ (though mpc)

# Help wanted!

Please, see the [issues](https://github.com/paulodiovani/media-player-control/issues) to know how to help.

Open new issues is also a good help.
