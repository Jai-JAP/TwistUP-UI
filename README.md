# TwistUP (For TwisterOS)
## The new, simple Twister OS patcher
AKA TwisterOS Patcher 2.0!
![](https://media.discordapp.net/attachments/738534235194916884/759921733825462322/TwisterOSPatcherLogo.png?width=960&height=186)<br>

## To download to the ~/TwistUP folder: 
```
git clone https://github.com/Botspot/TwistUP
```
## To download to the ~/patcher folder:
```
gio trash ~/patcher
git clone https://github.com/Botspot/TwistUP patcher
```
## To run:
```
~/TwistUP/twistup.sh
```
## Flags:
### Lists available patches and asks permission to update.
Intended for users who prefer patching "manually".
```
~/TwistUP/twistup.sh cli
```
### Just like above, but automatically applies the patch.
Intended to be used in non-interactive scripts.
```
~/TwistUP/twistup.sh cli-yes
```
### GUI Update mode.
If any patches are available, it uses a YAD dialog to display available patches and asks for confirmation. Also, this version opens a new terminal when installing a patch.  
```
~/TwistUP/twistup.sh gui-update
```
### GUI mode.
Uses a YAD dialog to display local version and latest version. If an update is available, this displays a Details button to install the patch.
Intended to be launched from the Menu.
```
~/TwistUP/twistup.sh gui
```
### GUI autostart mode.
If updates are available, this displays a notification on the bottom-right of the screen to let you know.  
This is run on start-up.
```
~/TwistUP/twistup.sh gui-autostart
```
