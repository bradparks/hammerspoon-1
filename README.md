# Hammerspoon .dotfiles

This is super messy, intend to clean it up and improve commenting soon
Comments/questions can be sent to hammerspoon [at] nonissue.org

## Functions:

### Window resizing/movement
* Resizes windows (fullscreen/halfscreen/75/25)
* Throws windows between monitors if there are two

### Resolution modification
* Can set resolution using modal hotkey
* Currently, possible resolutions are passed in manually from table of tables
* Creates a menubar item that displays current resolution width and when clicked, toggles between two most common for me to use

### Mail-to-self
* Hotkey bound to mail current Safari url to my email
* I use it for reading stuff later

### Pull current tab from safari
* Pulls current tab from safari and creates a new window with it

### User agent toggle
* Toggles user agent for safari for iOS dev
* Stolen from hammerspoon intro
* Modified to switch between default and iPad


## Todo
* [ ] Laptop resolution changing
* [ ] Battery alerts on laptop
* [ ] Change settings based on location (wifi ssid?)
* [ ] Better display of resolution options (ala hs.hints)
* [ ] grab active url from safari, send to clipboard?