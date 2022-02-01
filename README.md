# Mining Etherium Cryptocurrency While The Screensaver Is Active

This script will watch for the Gnome or the Xscreensaver screensaver to become active and start an Etherium CPU-based mining application running in the background.  When the screensaver is deactivated, i.e., someone unlocks the system and starts using it again, the script kills the mining application.

This script uses the Python pydbus module to watch for signals from the Gnome and Freedesktop screensavers.  It uses the <code>xscreensaver-command</code> application to monitor the activities of the Xscreensaver screensaver.
