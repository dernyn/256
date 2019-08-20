# 256 Font - all 256 characters (8-bits ASCII)... now fully visible! - The one of a kind font.
This Font works best with Western/Latin1 encoding of ISO-8859-1
CP1252/Windows-1252/IBM819/CP819/iso-ir-100/csISO-Latin1/ibm-5348

This Font is a retro style tribute to the IBM PC 5150 character set and TypeFace used in the U.S. (western) region by IBM's PC-DOS called CP437 with some modifications and adapted to be used with any version of the M$ Windows Operating System and Linux/Android (OTF version is in the works).This was made possible by utilizing available regions but often unused Unicode Mappings which most classic font implementations ignore in True-Type Fonts(.TTF) formats. As the name implies all 256 characters are mapped and can be used to view/display NON-PRINTABLE ASCII Characters normally hidden or made to be Ignored by all operating system enviroments and Text Editors due to the classic (default) ANSI standard.There is no other Unicode Font in the wild capable of doing this in the Windows/Linux OS since it's release in 2017, (Which is weird and may seem surprising to some). And Yes!, this Font allows you to visibly see the space character, tab and carriage return (CR+LF) in text editors by assigning the font to the txt-editors manually. in addition, all the other special characters outside the ASCII standard are available and visible with this font ... which is something most people don't understand and often can't not proccess/expressed/program properly by using text rendering libraries which are focused on the classic ANSI standard.
This font only works because of the TTF standard and the built-in support for Unicode's C0 + C1 regions and can be used in most classic operating that support .TTF formats and it's fonts.
<br>
![GitHub Logo](https://github.com/dernyn/256/blob/master/256.png)

More on the Font:

It is an ISO 10646-1(Unicode,BMP) encoded True-Type Font(TTF) -(Vector-based Glyphs,Unicode addressed) MS-Windows(.TTF)files- with full Extended ASCII-8 Support(ISO 8859-1) where the old ASCII-7 Standard of 128 characters is max-out and pushed further into the remaining 8bit addressing, allowing a 256 character region,like the IBM-PC 8-bit MGA card but in Font form.This font is utilizing Unicode C0 and C1 Controls provisional space instead of the Windows Bitmap-base .FON fonts of Windows 95/MS-DOS, which is what makes this font unique and one of a kind. There are changes to be made to this charset because glyphs are mapped in other unicode provisional spaces or canonical reserved Unicode addresses/regions (like U+2400 region-Control Pictures) which may conflict on a future improved CP437(ASCII8)+Unicode full BMP region combination ,basically one huge merged font of (this 256) plus the whole Unicode spectrum (all 65536 positions CP437 styled) in one file. 

<H3><b>Dedicated Regions:</b></H3>
C0 Controls Character U+0000-U+001F
<br>
</br>
C1 Controls Character U+0080-U+009F
<br>
</br>
I'm currently using the US codepage 437 character Style & Sequence of the standard with some customizations, which may change in the near future.
So, Think IBM OS-2/MS-DOS/PC-DOS CP-437(DOS Code Pages) or the idea of the classic Atari game maps made of 256 characters, where all 256 positions of the 8 bits are used, like the ISO 8859-1 standard.
In Unicode fonts, the actual keyboard character is linked to the glyph itself, which creates conflicts in the C0 and C1 Controls Regions, because they are already pre-provision elsewhere in unicode mapping in multiple different areas depending on standard such as; Western-Latin 1, etc., so if the unique keyboard character itself is used in the C0/C1 Controls areas they can't be re-used elsewhere in the unicode map or in the font file itself.(basically one keyboard char per glyph)

There are some customizations on some character 0x00 for 0x32 which makes the space character now a viewable character and 0x255 is my own creation.


<H3><b>The difference:</b></H3>
This is the original bitmapped windows version of the US codepage 437 without the unicode mappings, as you can see it's very limited,and it's non-unicode and non-truetype.

![GitHub cp437](https://github.com/dernyn/256/blob/master/cp437.png)


Future release:
add support for UTF-8 for Win/linux,
Monospaced version to use on the windows console (cmd.exe) with full 256 ASCII-8 support.
I also want to create a more normalized version without the viewable space character glyphs which may be annoying at times.

Testing the font is easy; apply the font to a txt editor and open the included file:
https://github.com/dernyn/256/blob/master/256.txt

![GitHub qt_test](https://github.com/dernyn/256/blob/master/qt_test.png)

For Example : Testing Qt Create on Debian Linux showing all 256 characters using the cp1252/ISO-8859-1 encoding, but any operating system with TTF and ISO-8859-1 encoding should do it.

License:


https://creativecommons.org/licenses/by-sa/4.0/

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

"tl;dr" version (which is not a substitute for the license on file):

You may freely share and adapt / transform / enhance them for any purpose listed by CC BY-SA 4.0
You must give appropriate credit (which includes the author's name and a link to the original material)
If you distribute your own adaptations, do so under a compatible license
No warranties are given - whatever you do, I will not be held liable

May you and others be Happy!

Thanks for your Support and appreciation.

dernyn -at- stonedcoder.org
