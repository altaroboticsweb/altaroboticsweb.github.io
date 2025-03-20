Links: [Hanabi](<https://github.com/jeffshee/gnome-ext-hanabi>), [Unblank lock screen](<https://extensions.gnome.org/extension/1414/unblank/>), [Desktop Cube](<https://extensions.gnome.org/extension/4648/desktop-cube/>),[Spotify Controls](<https://extensions.gnome.org/extension/7406/spotify-controls/>)
___
You should also download the `gnome-extensions-app` application so that you can see and modify all extensions, including manually installed ones. Each time you install one manually though you will have to restart gnome with either `Alt + F2` or rebooting your machine.

## Manual Install
For the ones that can't just be added using the [gnome extensions website](<https://extensions.gnome.org>)
### [Hanabi](<https://github.com/jeffshee/gnome-ext-hanabi>)
Animated background wallpaper player that uses javascript, can be installed with:
```bash
# Make sure you have the meson package installed
git clone https://github.com/jeffshee/gnome-ext-hanabi.git

cd gnome-ext-hanabi/

sudo apt install meson
./run install
```
It is recommended to configure what video that you want to play with `gnome-extensions` but you can also do it with this command, (this will play the video over all other apps though, may need to figure out how to put it in the back):
```bash
gjs /home/pizza2d1/.local/share/gnome-shell/extensions/hanabi-extension@jeffshee.github.io/renderer/renderer.js -P /home/pizza2d1/.local/share/gnome-shell/extensions/hanabi-extension@jeffshee.github.io -F [PATH_TO VIDEO_FILE] # ADD ABSOLUTE PATH
```
Wallpaper links: [HD2 Omens](<https://moewalls.com/games/helldivers-2-omens-of-tyranny-live-wallpaper/>), [HD2 Escalation](<https://moewalls.com/games/helldivers-2-escalation-of-freedom-live-wallpaper/>), [Vib-ribbon](<https://www.youtube.com/watch?v=HXD5pfonpNs>), [Kirby in pond](<https://moewalls.com/fantasy/yellow-kirby-floating-on-the-pond-live-wallpaper/>), [Bocchi the Rock](<https://moewalls.com/anime/kessoku-band-live-show-bocchi-the-rock-live-wallpaper/>)
🔐β 💡simple💡lWCMEcNZ3DmhKVgoqlbf62My87S6h1WjE75zRe+3qxDyE/BCfftz4MghuG0dAwbmRx5ZqTIxmuH61Q0C1uteHG3wJE3BEGY+2+JGMwz6Bi6erN0D+763y4ILvEgLVGy9IESlbcJi/Yli5TznudeF40XLRp5NyQyBOR59mDicXKgwGb/dzdf19gjcQx/3I156A+ArsjR+g1VfaNlMgWoTgvktyqtEj6UbAlbCw3ee4kLtJaiV8zRH26nRTHJ3rl3IsvpJ96iRvalW9lzvVQAZgBI= 🔐


___
## Automatic Install
For the ones that can just be added using the [gnome extensions website](<https://extensions.gnome.org>) by looking up the extensions

### [Unblank lock screen](<https://extensions.gnome.org/extension/1414/unblank/>)
A tool that will let you still see your background (although blurred) while logged out, rather than a gray login screen

### [Desktop Cube](<https://extensions.gnome.org/extension/4648/desktop-cube/>)
Will change the look of the workspaces by having them be 3D rather than sliding from one screen to the next

### [Spotify Controls](<https://extensions.gnome.org/extension/7406/spotify-controls/>)
Will show you the current song that is playing on spotify and allows you to click buttons on it that controls spotify media playing, will disappear when spotify is not open

### [System Monitor in Top Bar](<https://extensions.gnome.org/extension/120/system-monitor/>)
Will show CPU, Memory, and Swap usage in top bar

### [Computer battery limiter](<https://extensions.gnome.org/extension/5724/battery-health-charging/>)
Will prevent the battery from charging past a certain point for longevity

### [Bluetooth battery display](<https://extensions.gnome.org/extension/6670/bluetooth-battery-meter/>)
Shows all battery levels of connected bluetooth devices