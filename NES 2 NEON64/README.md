# NES 2 NEON64 Converted Patches.

Here are Patches for use with [xdelta](http://xdelta.org/) command-line tool and for ease of use [xdeltaUI](https://www.romhacking.net/utilities/598/) The Windows FrontEnd.

Make sure your Games are the correct name and file type before patching!

Please check the ReadMe in that section for further information.

Note: If anyone is experiencing issues with my patches and the newer versions of the Retro Stage's [N64 Blaster 2.0](https://retrostage.net/?product=n64-blaster-2-0) because of the Automatic CIC, Region, I advise either using the [old version with the dip switches](https://web.archive.org/web/20210622192800/https://retrostage.net/?product=n64-blaster-2-0)  or using Benn Venns excellent [JoeyN64 cart flasher](https://bennvenn.myshopify.com/products/joeyn64-cart-flasher) and clone flashing method.

Please also be advised that if you intend to use games with FlashRam saves, the N64 Blaster really is not suitable for this as it has no FlashRam support. Instead i advise using another product that does like the Benn Venns excellent [JoeyN64 cart flasher](https://bennvenn.myshopify.com/products/joeyn64-cart-flasher).

All of these patches are to be used with CIC-NUS-6102 (NTSC) / CIC-NUS-7101 (PAL) SRAM and any clone cart within that section can be used:

Visit the [Gent's Joey64 Clone Cart - CIC & Save Type Guide](https://github.com/TheGent/Gents-N64-xdelta-Patches/blob/main/Gent's%20Joey64%20Clone%20Cart%20-%20CIC%20%26%20Save%20Type%20Guide.md) and search for (Ctrl+F) CIC-NUS-6102 (NTSC) / CIC-NUS-7101 (PAL) SRAM


Ok so what is NEON64 you say?

Neon64 2.0 beta 4 WIP
=================

Features include
--------

- NTSC and PAL NES on NTSC N64 (and now using these patches) on the PAL N64 console, as actual N64 games, no external emulator required!
- CPU (official opcodes)
- PPU
- APU channels (2 square, triangle, noise, DMC)
- Battery backed RAM save to SRAM
- iNES mappers #s 0,1,2,3,4,7,9,10,11,30,31,34,66,71
- Controllers 1 and 2  (D-pad + analogue)
- Built in Debug by using Left+Right trigger buttons together on your controller.

The debug menu can be handy if video is slightly still off, then you can boot in the opposite modes NTSC/PAL Mode)

Now to patch these could not be simpler, you navigate to the section you are looking for:

NTSC CONSOLE (To be used with an NTSC Console Only)

- (E) (European PAL NES Games on an NTSC N64 System)
- (JU)(Native NTSC System)
- (U)(Native NTSC System)


PAL CONSOLE (To be used with a PAL Console Only)

- (E)(Native PAL System)
- (JU) (USA/JAPAN NES Games on a PAL N64 System)
- (U) (USA  NES Games on a PAL N64 System)

I would like to thank [Adam Gashlin](http://xdelta.org/) for the [neon64](https://hcs64.com/neon64.html) project!
Without it, these patches to play NES on N64 would not have been possible.

Thank you very much Adam

Please read the README's in each section to explain what the base ROM is and how to patch these for your NES2N64 pleasure

Regards
[Gent](https://github.com/TheGent)





