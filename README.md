# Hi! I'm Gositi.

Welcome to my GitHub.
I usually program in Python and C, but I have also dabbled a bit in assembly programming.
The kinds of projects that I have made is pretty diverse, although most of my repos are private.
Below is two examples of projects that I am (currently) extra proud of.

## minesweeper-os
This is intended to be a bootable minesweeper game, but so far it is just a snake game.
Currently a bootloader written in assembly with some useful I/O functions is written, as well as a proof-of-concept snake game in assembly.
The snake game was both made for fun, but also to showcase the bootloaders functions for randomness and I/O.
The actual minesweeper game is planned to be written by adapting existing C code, but this work is not completed yet.

## discord-fs
This is a project allowing you to use Discord as "cloud storage".
It mounts a virtual Linux filesystem, that uses message file attachments on Discord to store data.
It integrates pretty well with the filesystem, but the up- and downloads are of course quite slow.
Also there is no support for directories.
