# i3lock-mod - modified improved screen locker
i3lock-improved is a fork of the i3lock screen locker.
Unlike the original i3lock, you can execute shell commands on wrong password input, what comes
in handy when you want to do cool stuff like taking a picture of the person
trying to access your computer without permission.

## Requirements
- pkg-config
- libxcb
- libxcb-util
- libpam-dev
- libcairo-dev
- libxcb-xinerama
- libev
- libx11-dev
- libx11-xcb-dev
- libxkbcommon >= 0.5.0
- libxkbcommon-x11 >= 0.5.0

## Usage example
Add this line to your local i3conf (or execute it where you want):

``bindsym $mod+Escape exec --no-startup-id /path/to/i3lock-mod/./i3lock -f -s '/path/to/i3lock-mod/sample_script.sh'``

In this example: Lock your screen with mod+Escape.

## Sample script
The sample script takes a photo with the webcam via streamer

## Contributing
Consider commiting your Pull Request on the main i3lock repository.
