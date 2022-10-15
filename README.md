# Minecraft Redstone Computers Schematics
Here's some Minecraft computers I made

To test these computers, you have to download a schematics Minecraft mod as [Schematica](https://www.curseforge.com/minecraft/mc-mods/schematica), [Litematica](https://www.curseforge.com/minecraft/mc-mods/litematica), [World Edit](https://www.curseforge.com/minecraft/mc-mods/worldedit/)...
Then go in `.minecraft/config/<mod name>/schematics` or`.minecraft/schematics` it'll depends on the mod and the version.
And finally you can launch the game, and go in a minecraft world using the Schematics mod to load and print the schematic file.

## 1. Fibonacci
A compact computer made with an adder, two registers, and a sort of accumulator to manage output. The dashboard is three-parted:
- Manual Clock
- Automatic Clock
- Reset

The first enables the user to define the clock rate. Then the second enables an almost perfect defined clock rate. And the last is used to reset the whole computer.

Note: The highest lamp on the output symbolizes overflow.

## 2. Character by character [polybius square](https://en.wikipedia.org/wiki/Polybius_square)
A not so compact computer with a twenty-five cells RAM for storing the polybius square, an address and a data bus. Then connected to the bus, two computing cells, one for encrypting a character, the other one for decrypting those. The goal is to input a character, return the coordinates in the square and then be able to get back the character from the address.
Characters are encoded on 2 bytes, address on 6 bits (3+3). For more docs about the computers, I recommend you to read in game the books available.

Note: If you want to use it at its full potential you'll need to instantiate cells, one-after-one. For now only some are instantiated.

