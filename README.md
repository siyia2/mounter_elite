![2023-10-27-102009_grim](https://github.com/siyia2/mounter_elite/assets/46220960/b6f17616-8489-4694-9ec7-274a3664c40b)



## ELITE IMAGE MOUNTER

Simple asf bash script, that allows you to mount `ISOs` and/or to `convert` `BIN/IMG` files to `ISO`. Path prompt supports `Tab Completion`, just point it to the correct path and shoot enter.
You can add multiple mount or conversion paths, all valid paths are mounted under `/mnt/` and `all conversions take place in their respective source directories`.

I have also included options to unmount the mounted `ISO` or `ISOs` and a choice for opening the `/mnt/` directory directly from the script.

In addition i have added since v1.2 and up an option to generate an image list under a user prompted path, it can significantly help in mounting or converting the images en masse, with the help of the clipboard

For the conversions, `ccd2iso` is used, i tested it with some `valid IMG and BIN` files through my script and it works.

The AUR executable is installed in `/usr/bin/mounter_elite`.
