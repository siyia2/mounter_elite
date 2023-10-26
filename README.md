![2023-10-26-204132_grim](https://github.com/siyia2/mounter_elite/assets/46220960/0ec531f1-f580-4979-988e-219806415696)


## ELITE IMAGE MOUNTER

Simple asf bash script, that allows you to mount `ISOs` and/or to `convert` `BIN/IMG` files to `ISO`, just point it to the correct path and shoot.
You can add multiple mount or conversion paths, all valid paths are mounted under `/mnt/` and `all conversions happen in the original file directory`.

I have also provided options to unmount the mounted `ISO` or `ISOs` and a choice for opening the `/mnt/` directory directly from the script.

For the conversions, `ccd2iso` is used, i tested it with some `valid IMG and BIN` files and it works.

The executable is installed in `/usr/bin/mounter_elite`.
