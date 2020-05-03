# CreateUbuntuShortcut
Create ubuntu shortcuts easily without much effort over terminal for gnome environment

This can be executed directly from the GNOME desktop directory or be inserted to bin directory.<br><br>

To insert this bash script into the bin dir, follow these steps:<br>
Open the terminal.<br>
To enable desktop icons, the gnome tweak tool has to be installed first:<br>
`sudo apt-get install gnome-tweak-tool gnome-tweaks`<br>
In there, search for "icon", then go on Desktop and enable the option called "Desktop Symbols"<br>
Since aptitude is needed, if you don't have it already installed, install it via the terminal:<br>
`sudo apt-get install aptitude`<br>
Navigate to the Desktop via cd command in terminal<br>
Create a new file:<br>
`touch createshortcut.run`<br>
Open the file and copy the file into there.<br>
Then move file to /usr/bin with:<br>
`sudo mv createshortcut.run /usr/bin/createshortcut`<br>
Make the file executable:<br>
`sudo chmod +x /usr/bin/createshortcut`<br><br>

Everything is done so far!<br><br>
To create shortcuts in .desktop format you just have to execute `createshortcut` when navigated in the desktop folder in the terminal (this can be done via the `cd` command or right-click on desktop -> "open terminal here") and follow the steps!
