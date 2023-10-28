![2023-10-27-185239_grim](https://github.com/siyia2/mounter_elite/assets/46220960/2a62faf6-bab2-4f26-be66-f980af8ab6d4)




## ELITE IMAGE MOUNTER

Simple asf bash script, that allows you to mount `ISOs` and/or to `convert` `BIN/IMG` files to `ISO`. Path prompt supports `Tab Completion`, just point it to the correct path and shoot enter.
You can add multiple mount or conversion paths, all paths are mounted under `/mnt/` and `all conversions take place in their respective source directories`.

I have also included options to unmount the mounted `ISO(s)` and a choice for opening the `/mnt/` directory directly from the script.

Since `v1.2` and up, i have implemented a `search based list` for options `1&4` to locate and display the `ISO BIN IMG` files, it `significantly speeds up the processing of images en masse, with a little help from the clipboard.`

Since `v1.4` everything is parallelized to improve performance.

For the conversions, `ccd2iso` is used, i tested it with some `valid IMG and BIN` files through my script and it works.

The AUR executable is installed in `/usr/bin/mounter_elite`.
