# mpd-notify v0.1
+ Notifications on song change, play, and pause.
+ Automatic cover art detection\*
+ Automatic cover art fetching
+ Updates wallpaper on song change
+ Volume notifier
+ Daemon

\* This only works if you have seperate folders for every album and cover art in that album. But you're not some sort of monster, right?

### Screenshot
![Screenshot](screenshots/screenshot2.png?raw=true)

## Installation
Run install.sh and edit the config at $HOME/.mpd-notify/mpd-notify.cfg. "mpd-notify start & disown" to start.

### Dependencies
MPD, MPC, notify-osd, notify-send, [Python3, pip3, requests], [feh, imagemagick]. Recommend <a href="https://launchpad.net/~leolik/+ archive/ubuntu/leolik">leolik's notify-osd</a> as it respects timout commands.

## Roadmap
+ Better/"real" daemon
+ Add notifs for repeat, random, single, consume
