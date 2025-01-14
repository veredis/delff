# Delete Firefox (for Linux)

This is the easiest way I could find to automate the uninstallation of Firefox on Linux.
The main file is just several terminal commands merged into one.

The tool automatically deletes itself after use.

# Instructions

Run the contents of the delff file in a Linux terminal.

***Warning:** This tool is meant for fresh installs, as it removes all mentions of "firefox" on the system. This may cause issues if there are other files with "firefox" in the name.*

## Ways to do this:

### CLI / Git Method:

1. Open terminal
2. Type `git clone https://github.com/veredis/delff`
3. Type `sh delff/delff`

### Copy/Paste

* Just copy all the text in the [delff file](https://github.com/veredis/delff/blob/main/delff "delff") and paste it into the terminal

### Manual Download

* Download the [delff file](https://raw.githubusercontent.com/veredis/delff/main/delff "delff") and type `sh delff` into the terminal

## Why delete Firefox? Why make a tool?
I prefer Brave; and this will minimize the number of steps required to fully uninstall FF when testing out distros.

---

#### Tested on:
* Pop!\_OS, which is Debian/Ubuntu-based
* Linux Mint, which is Debian/Ubuntu-based
* EndeavorOS, which is Arch-based
* Manjaro, which is Arch-based
