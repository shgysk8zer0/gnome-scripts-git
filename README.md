# gnome-scripts-git
A collection of Gnome Scripts for Git. **Linux only**

- - -

![Screenshot](https://i.imgur.com/iTP83P2.png)

## Contact author
- [Report issue](https://github.com/shgysk8zer0/gnome-scripts-git/issues/new)
- [Email](mailto:shgysk8zer0@gmail.com?subject=gnome-scripts-git)

## Available commands
- checkout
- stage
- unstage
- remove
- untrack

## Installation
- Enter Gnome scripts directory: `cd ~/.local/share/nautilus/scripts/`
- Clone: `git clone git://github.com/shgysk8zer0/gnome-scripts-git.git git`
- Scripts **should** now be added to context-menus when right-clicking on files

*If this does not work, you may have to manually set executable permissions on
each of the scripts.*

## Wants and limitations
I would like to extend the functionality as much as is possible, but am not sure
if certain commands, such as those where text output is essential or those that
apply to an entire repository are possible. For anything that has important text
output, such as `git status`, there is need of a way of presenting this info.
Commands, such as `git clone`, that do not apply to individual files or directories,
but rather entire repositories are not likely to ever be included.

## Contributing
Contributions are welcome through pull-requests. You may request any command you
would like added by submitting it as an [issue](https://github.com/shgysk8zer0/gnome-scripts-git/issues/new).
