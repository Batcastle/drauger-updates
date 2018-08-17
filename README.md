# drauger-updates
This repo stores all the data necissary to update Drauger OS using the built in `update-os` command.

Folders named `leg(some_number)` are old updates, kept for those who may not have run `sudo update-os -u` yet.
The lower the number the older the update.

To update a computer running Druager OS from this repo, open a terminal by pressing Ctrl+Alt+T

Available commands include:

* `sudo update-os -u` to download and install updates
* `sudo update-os -c` to check for updates
* `update-os -s` to view the downloaded update script and see what updates there are
* `sudo update-os -i` to manually run the currently downloaded update script
* `update-os -h` to see the help dialogue

A graphical user interface for this function will be availble starting Drauger OS 7.4.1 Beta 2
