# Bibi-Game-Boy
Bibi the Game Boy Game.

## Compilation
Built with Z80 assembly and assembled with [RGBDS](https://github.com/rednex/rgbds "RGDBS")

Install the RGBDS toolkit for your OS.

Run the following commands to build the gb ROM.

```
rgbasm -o bibi.obj bibi.z80
rgblink -m bibi.map -n bibi.sym -o bibi.gb bibi.obj
rgbfix -p 0 -v bibi.gb
```

## Play Time
Run the ROM in your favourite emulator.

Or even better, flash the ROM to a gb flash cart and play on real hardware. [Derp Cart](http://derpcart.com/)