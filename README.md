# WSL-GUI
Run WSL with GUI

## Installtion steps：

** Please check all code in this repository to make sure it is safe. **

1. [Install Cygwin](https://cygwin.com/install.html) on Windows.
2. Install `xlaunch`(will include xserver) in Cygwin setup programing.
3. Copy all files from [windows directory](https://github.com/libook/WSL-GUI/tree/master/windows) to somewhere on Windows.
4. Install `terminator` in WSL.
5. Copy `start_terminator` from [root directory](https://github.com/libook/WSL-GUI/tree/master/root) to root directory in WSL.

## Useage:

1. Double click `config.xlaunch` and then make sure there is a icon of X Server on your tray area. (You can add a shortcut of this file into the `Startup` folder which is in `Start menu` to let it run on each startup)
2. Double click `WSL.lnk`.

And then, you can see a GUI of terminator. Just run any software in terminator, you will see the GUI if there is one.