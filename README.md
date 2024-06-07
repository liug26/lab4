# Hey! I'm Filing Here

In this lab, I successfully implemented:
A file system consisting of a root directory and another directory, 1 regular file, and its symbolic link, implemented through changing the functions in ext2-create.c

## Building

To build, run the command `make`

## Running

./ext2-create
dumpe2fs cs111-base.img
    (then check for output and compare it against the provided output)
fsck.ext2 cs111-base.img
    (then check for errors in its output)
mkdir mnt
sudo mount -o loop cs111-base.img mnt
sudo umount mnt
rmdir mnt


## Cleaning up

To cleanup, run the command `make clean`
