# ROFI-MPD
Rofi-mpd aims to provide a fast, keyboard-driven way to interact with the music play daemon. It uses rofi to list artists, albums etc. It does not intend to provide a full replacement for graphical mpd-clients.

## INSTALLATION
place `rofi-mpd` to your path (`/usr/bin/, ~/.local/bin/`, etc)

## USAGE
```sh
$ rofi-mpd [option]
```

## COMMAND LINE ARGUMENTS
```sh
-a, --artist 	  	search for artist, then album, then title
-t, --track 	  	search for a single track in the whole database
-p, --playlist   	search for a playlist load it
-j, --jump       	jump to another song in the current playlist
-l, --longplayer	search for album, then title
```

## Preview
![preview1](https://github.com/fikriomar16/rofi-mpd/raw/master/preview1.png)
![preview2](https://github.com/fikriomar16/rofi-mpd/raw/master/preview2.png)

## Credits
[bubbl3gum](https://github.com/bubbl3gum/mpd_control)

## .Xresources
[.Xresourcxes](https://github.com/fikriomar16/dotfiles/blob/master/.Xresources)

## License
The code is available under the [MIT License](https://github.com/fikriomar16/rofi-mpd/blob/master/LICENSE.md)
