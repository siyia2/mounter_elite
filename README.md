
![2023-10-29-205418_grim](https://github.com/siyia2/mounter_elite/assets/46220960/b8fac24a-6617-4f03-8ba6-0dd34dbb6284)



## ELITE IMAGE MOUNTER

Simple asf bash script, that allows you to mount `ISOs` and/or to `convert` `BIN/IMG` files to `ISO`. Path prompt supports `Tab Completion`, just point it to the correct path and shoot enter.
You can add multiple mount or conversion paths, all paths are mounted under `/mnt/` and `all conversions take place in their respective source directories`, script requires `ROOT` access to mount and unmount ISOs.

I have also included options to unmount the mounted `ISO(s)` and a choice for opening the `/mnt/` directory directly from the script, using your default file manager.

Since `v1.2` and up, i have implemented a `search based list` for options `1&4` to locate and display the `ISO BIN IMG` files, it `significantly speeds up the processing of images en masse, with a little help from the clipboard.`

Since `v1.4` everything is parallelized to improve performance.

Since `v1.5` there is full list intergration inside options `1&4`, no need to copy paste or use the clipboard, just enter numbers from the generated list.

For the conversions, `ccd2iso` is used, i tested it with some `valid IMG and BIN` files through my script and it works. If `ccd2iso` cannot convert the images or the images are corrupt, i can't do anything about it.

The AUR executable is installed under `/usr/bin/mounter_elite`.
