# cava colorchanger

Script that will automatically change the color of the cava visualizer bars according to the color of the current album art of any media player that implements the [MPRIS](http://specifications.freedesktop.org/mpris-spec/latest/) D-Bus Interface Specification.

## Running

```sh
playcheck.sh & cava
```

## Demo

![](https://i.imgur.com/vHlsZhK.gif)

## Requirements

- [cava](https://github.com/karlstav/cava)
- imagemagick
- [playerctl](https://github.com/acrisci/playerctl)
- wget

## Original script
The orginal script is coded by [kb-elmo](https://github.com/kb-elmo/cavapify). Spotify's album cover url has changed and I used sed to point to the updated one. Due to kb-elmo not yet acepting the pull request, I created this fork to use cavapify with spotify.
