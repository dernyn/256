# 256 - Font, Displays all 256 characters (8-bits ASCII) in Text Controls/Editors/TTY - The one of a kind font.
This Font works best with character Region English - Western/Latin1 encoding providing single-byte character encoding with
CP1252/Windows-1252/IBM819/CP819/iso-ir-100/csISO-Latin1/ibm-5348 and ISO-8859-1 depending on Text editor support.

This Font does not support UTF-8 encoding, Inherently Fails to fully encode in UTF-8 due to it's native lack of single-byte character support by the standard, which is limited to ASCII-7 (128).

This Font is a retro style tribute to the IBM PC 5150 character set and TypeFace used in the English - Europe/U.S. (Western/Latin1) "region" by IBM's PC-DOS called CP437 with some modifications and adapted to be used with any version of the M$ Windows Operating System and Linux/Android (OTF version is in the works).This font was made possible by utilizing all available regions in the Unicode BMP spectrum/glyphs this let's user have the ability to leverage encoding schema using Text editors that can read Windows-1252 encoding of all 8-bits, with most other fonts, all available glyph spaces are not defined or unused in there Unicode Mappings, most classic font implementations ignore the ability to do so in True-Type Fonts(.TTF) formats particularly. As the name implies all 256 characters are mapped and can be used to view/display NON-PRINTABLE ASCII Characters, particularly extended ASCII (ASCII-8); These characters are normally/inherently hidden or made to be Ignored by all operating system enviroments and Text Editors due to the classic nature of the ANSI standard implementation by default and the internalized functional mappings of Control characters in OSes.There is no other Unicode Font in the wild capable of doing this in the Windows/Linux OS since it's release in 2017, (Which is weird and may seem surprising to some). And Yes!, this Font allows you to visibly see the space character, tab, Line Feed, carriage return (CR+LF) in text editors by assigning the font to the text-editors manually by the user. In addition, all the other special characters outside the ASCII-7 standard are available and visible with this font ... In my view is something most people don't understand and often can't not proccess/expressed/code properly by using text rendering libraries which are focused on the classic ANSI standard/support.
This font only works because of the TTF/Windows-1252 standard and the built-in support for Unicode's BMP C0 + C1 available regions, This Font can be used in most classic 32-bit operating Systems that support .TTF formats and it's Unicode fonts.
<br>
![GitHub Logo](https://github.com/dernyn/256/blob/master/256.png)

More on the Font:

It is an ISO 10646-1(Unicode,BMP) encoded True-Type Font(TTF) -(Vector-based Glyphs,Unicode addressed to all 256 spaces) supports Linux/MS-Windows 32/64 bit(.TTF) standard - with full Extended ASCII-8 Support(CP-1252/ISO 8859-1) where the old ASCII-7 Standard of 128 characters is max-out and pushed further into the remaining 8-bit addressing scheme called single-byte character addressing, allowing a 256 character map, like the old IBM-PC 8-bit MGA cards but in Unicode Font form-factor. This font is utilizing Unicode C0 and C1 Controls provisional space instead of the Windows Bitmap-base .FON fonts of Windows MS-DOS/3.1/NT/95/98, which is what makes this font very unique and one of a kind. There are changes to be made to this charset because glyphs are mapped in other unicode provisional spaces or canonical reserved Unicode addresses/regions (like U+2400 region-Control Pictures) which may conflict on a future improved CP437(ASCII8)+Unicode full BMP region combination ,basically my idea is to continue to fill the entire BMP region in this font with what is there available for other language regions and creating one huge merged font with 256 plus the whole BMP Unicode spectrum (all 65536 positions) in one file. 

<H3><b>Dedicated Regions:</b></H3>
C0 Controls Character U+0000-U+001F
<br>
</br>
C1 Controls Character U+0080-U+009F
<br>
</br>
I'm currently using the US codepage 437 character/glyphs Style & Sequence of the standard with some customizations of my own, which may change in the near future.
So, Think IBM OS-2/MS-DOS/PC-DOS CP-437(DOS Code Pages) or the idea of the classic Atari game maps made of 256 characters, where all 256 positions of the 8 bits are used in games, like the ISO 8859-1 standard but better.
In Unicode fonts, the actual keyboard character is linked to the glyph itself, which creates conflicts in the C0 and C1 Controls Regions since the characters are absent in modern keyboards, often the characters are pre-provision elsewhere in unicode font mapping in multiple different areas depending on standard such as; Western-Latin 1, etc., so if the unique keyboard character itself is used in the C0/C1 Controls areas they can not be re-used elsewhere in the unicode map or in the font file itself.(basically one keyboard char per glyph)

There are some customizations on some character 0x00 for 0x32 which makes the space character now a viewable character and 0x255 is my own weird creation, along with others.


<H3><b>The difference in CP437/CP1252:</b></H3>
This is the original bitmapped windows version of the US codepage 437 without the unicode mappings, as you can see it's very limited,and it's non-unicode and non-truetype file-based, without Vector/anti-aliasing, etc.

![GitHub cp437](https://github.com/dernyn/256/blob/master/cp437.png)


Future release:

OpenType Fonts (OTF) version,maybe....
alternative character sets for other regions;
Monospaced version to use on the windows console (cmd.exe) allowing a nice uniform view of all 256 characters/ASCII-8 support.
I also want to create a more normalized version without the viewable space character glyphs which may be annoying at times or to some.

Testing the font is easy; apply the font to a txt editor and open the included file:
https://github.com/dernyn/256/blob/master/256.txt

![GitHub qt_test](https://github.com/dernyn/256/blob/master/qt_test.png)

For Example : Testing Qt Create on Debian Linux showing all 256 characters using the cp1252/ISO-8859-1 encoding, This also works with QT in Windows!, but any operating system with .TTF and CP-1252/ISO-8859-1 encoding should do it.


<b>WHY!? make this!: </b>
Well, You can now edit ALL! your files with a Text Editor; Binaries and or non-binaries without a Hex Editor; 

Perhaps view Binary Packet content in Text form in Wireshark

or view a binary output in a Console Window/Terminal in X-11-Gnome/M$-Windows (althought the control characters may trigger internal functions).  

Put it in an IDE and see those pesky special characters that trigger errors and alterior behaviours.

The point is simple!, you have more options!

-brain-blowing emoji here-

![GitHub notepad](https://github.com/dernyn/256/raw/master/256%20-%20Notepad.png)

a windows Binary file in the Windows 10 Native Notepad.exe 

WTF! why was this missing again?

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
