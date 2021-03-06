# xAmp
Cross platform youtube video player with an independent playlist from youtube.

![xAmp screenshot](https://i.imgur.com/5o6wi69.png)

The internal playlist isn't tied to playlist text files, modifying the internal playlist won't make any file changes unless you save them, but the current playlist will be saved separately.

Opening a playlist will overwrite the internal playlist, not add to it.

## Hotkeys (some of these don't work on macOS)
- `space`: play/pause the video
- `ctrl` + `arrow right`: next video
- `ctrl` + `arrow left`: previous video
- `ctrl` + `arrow up`: volume up 10%
- `ctrl` + `arrow down`: volume down 10%
- `ctrl` + `s`: save current playlist
- `ctrl` + `o`: open playlist
- `delete`: delete selected video from internal playlist
- `shift` + `arrow up`: move selected video up in internal playlist
- `shift` + `arrow down`: move selected video down in internal playlist
- `arrow up`: select the next video up, or the top/first video if no video is selected
- `arrow down`: select the next video down, or the bottom/last video if no video is selected
- `esc`: unselects any video and clears input text

## Running in Windows x64

1. Go to the [releases](https://github.com/Skhmt/xAmp/releases) page and get the latest .zip named something like: `xAmp-#.#.#-win-x64.zip`
2. Extract everything and put it anywhere
3. Run `xAmp.exe`
4. If the `Windows protected your PC` window comes up, click `More info` then `Run anyway`

## Running in macOS

1. Go to the [releases](https://github.com/Skhmt/xAmp/releases) page and get the latest .zip named something like: `xAmp-#.#.#-macOS.zip`
2. Extract everything and put it anywhere
3. Right-click `xAmp` and click `Open`
4. Click `Open` in the popup window

## Building (Optional unless you're on linux)

1. Download [nw.js](https://nwjs.io/)
2. Place everything into a folder named `package.nw`
3. Place that folder into `nw.js`'s folder
4. Run it
