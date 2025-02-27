# Z-Machine interpreter (with some additions)

Python 3 implementation of a z-machine interpreter, for playing Infocom games. To play a z-machine file:

`python zmachine [GAME_FILE]`

The interpreter supports z-machine versions 3, 4 and 5. Version 4 games include Trinity, AMFV, and Bureaucracy. Version 5 games include Border Zone and Beyond Zork. Save files are in [Quetzal](http://inform-fiction.org/zmachine/standards/quetzal/index.html) format and should be compatible with the Frotz interpreter.

The original Zork trilogy (written by Tim Anderson, Marc Blank, Bruce Daniels, and Dave Lebling) is in the `games` directory.

## Additions

The program will read commands from a file named "input.txt", and it will send all output to a file called "output.txt". It does not word wrap, and will not display screen output correctly. "are you sure" will be answered with a Y and [press any key to quit] is completely skipped. >q and the "y" and the confirm and the exit prompts will not be saved in the output file.

## Further notes

The [Z-Machine Standards Document](https://www.inform-fiction.org/zmachine/standards/z1point1/index.html), by Graham Nelson, is an indispensable guide for decoding the z-machine instructions.

This space intentionally left blank.
