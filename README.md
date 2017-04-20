shapht-syntax
===========

SHAPHT syntax highlighting package for [Sublime Text 3](https://www.sublimetext.com/3).


For users
---------

Recommended: Install [PackageControl](https://packagecontrol.io/).
Then open the command palette (default keybinding: `Cmd+Shift+P`), select `Package Control: Install Package` and choose `SHAPHT Syntax`.

Manual (not recommended): Click on "Download ZIP", extract the archive into sublime's package folder, e.g. `~/.config/sublime-text-3/Packages/User/`.


For developers
--------------

If you want to change something, you need to install AAAPackageDev for sublime and then:

* edit `shapht.JSON-tmLanguage`
* run *build* in Sublime and select *Convert to: Property List*
* increment version number in `packages.json`

In order to test your changes, you can symlink the repository to sublime's package folder, e.g.

    $ ln -s /tmp/shapht-syntax/ ~/.config/sublime-text-3/Packages/User/


Feel free to send merge requests!
