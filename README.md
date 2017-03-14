# TinTin++ FANSI Patches

## Background
This patch was written for 8bit.fansi.org (8 Bit MUSH)

## Applying Patches
To apply these patches, you should be in the directory
containing the tt source directory.

patch -s -p0 < tt-2.01.2-fansi.patch

## Installing Fonts
You will need a special font which maps the CP437 chars
to the corresponding UTF-8 listed in the table here.
https://en.wikipedia.org/wiki/Code_page_437

If your terminal can handle TrueType fonts.
http://int10h.org/oldschool-pc-fonts/

If you can't use TTF, or would rather use bitmaps.
Install the rom.pcf font I have provided, precompiled.

## Using
When you want to see all the FANSI art, just do:
#config fansi on

## License
As the original project is GPLv2, these changes are also
licensed GPLv2 or higher.
