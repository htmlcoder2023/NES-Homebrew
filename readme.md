Decimal - Base 10, with a number system as 100, 10, 1. Basically if you remove a zero a number is 10 times smaller.

Binary - Base 2, with a number system as 4, 2, 1. Binary numbers look something like this: 11111110 and if a zero was removed, the number becomes 2 times smaller.

Hex - Base 16, with a number system as $100 (or 256), $10 (or 16), and 1. Makes binary obsolete for coding purposes.



Memory - The NES can access 2^16 bytes of memory, or 65,536 bytes.

Instructions - The NES processor only has 56 instructions.

Variables - A place that store data that can be modified.

Control flow - When an instruction is run based on a variable, kind of like: if x is this, then x happens, else, x happens. 



KB - 1 kilobyte is 1024 bytes, and 1 byte is 8 bits. 

ROM - The result of the compiled assembly code, and also what is used to play NES games. The ROM should be 40,976 bytes, with the INES header being 16 bytes. 

RAM - Holds data that can be read and written. Without a battery, when the power is removed, the data in the RAM is erased.

PRG - Program code for the game, which is 32,768 bytes.

CHR - Graphics data for the game, which is 8,192 bytes.

CPU - The main processor for NES. All cycles are either read or write. 

PPU - Contains 10 kilobytes of memory, which contains 2 kilobytes of RAM and 8 kilobytes for CHR-ROM or CHR-RAM. It displays a video signal.

APU - Where sound is processed.



4-screen RAM - Holds 4 screens of background instead of 2 screens. It is not common.

WRAM - Also called Work RAM, it is used to save games. Not common.

Lockout Chip - It controls the resetting of the console, and there are 4 versions of the lockout chip. If the revision number is 05, it has the least lockout-defeater protection, if the revision number is 07 and 09, it has some lockout protection, but if the revision number is 11, it has the most lockout protection and most lockout defeaters fail.



Tiles - All graphics are made up of 8x8 tiles. The advantage of the tile system is that less memory is needed, but 3D graphics aren't possible.

Sprites - The PPU has enough memory for 64 sprites, but no more than 8 sprites can be on-screen at a time.

Background - Sprites can either be displayed in front or behind the background, and there is enough internal RAM to hold 2 screens of background. 

Pattern Tables - They are either stored on the CHR-ROM or CHR-RAM of the cart. Each pattern table holds 256 tiles, with one table holding background info and another holding sprite info.

Attribute Tables - These tables set the color info in 2x2 sections, meaning a 16x16 section can only hold 4 different colors from the palette.

Palettes - These two areas hold color information, one from the background and one from the sprites. The palette has 16 colors.