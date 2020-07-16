How can I launch gnome-terminal remotely on my headless server? (fails to launch over X11 forwarding)
https://unix.stackexchange.com/questions/407831/how-can-i-launch-gnome-terminal-remotely-on-my-headless-server-fails-to-launch
export $(dbus-launch)
gnome-terminal

