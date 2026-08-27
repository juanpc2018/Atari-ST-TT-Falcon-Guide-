# Atari ST TT Falcon Guide 
v0.0000001 </br>

### Atari vs. Amiga vs. Apple </br>
were very similar, but... </br>
different ways of creating a different experience around the Motorola 68K CPU. </br>
"who builds a better [Exoskeleton](https://en.wikipedia.org/wiki/Exoskeleton) around it." </br>

Atari ST = Amiga 500, basic model same Motorola 68k 000 CPU, same speed. </br>
there were different variants / upgrades to the ST,
STF = Floppy, STFM = Floppy + TV Modulator output. </br>
STE improved [Blitter](https://en.wikipedia.org/wiki/Blitter) Graphics Chip. </br>
Mega ST 1,2,4 = 1MB, 2MB, 4MB "on a Slim Horizontal Desktop case, but Not really a desktop with many expansion slots" </br>
Mega STE improved MegaST. </br>
[Atari TT 030 (1990)](https://en.wikipedia.org/wiki/Atari_TT030) = Amiga 3000 by date 1990, and some features. </br>
[Atari Falcon 030 (1992)](https://en.wikipedia.org/wiki/Atari_Falcon) = Amiga 1200 (1992) </br>

some differences: </br>
STe versions had Blitter chip to accelerate graphics, </br>
Not included on the TT, </br>
TT had a different Graphics Shifter accelerator, </br>
Blitter was re-introduced again on the Falcon. </br>

Mega STe, Falcon & TT were The Best & Last machines produced by Atari. </br>
after personal computer era, Atari focused on Gaming consoles, similar to Amiga CD32. </br>

**Differences:**  </br>
Falcon has Motorola DSP56001, used in many HW Digital Synths & ProTools TDM, </br>
but can be used as Graphics co-processor / accelerator for Floating Point math: fractals, 3D render, etc.. </br>
TT has Finally a True Next Gen Expansion port: [VMEbus](https://en.wikipedia.org/wiki/VMEbus) </br>
Falcon CPU can be upgraded similar to Amiga, </br>
TT has soldered CPU. </br>

TT has optional [TenoxVGA](https://github.com/tenox7/tenoxvga) & [ATW800/2](https://www.geekdot.com/atw800_2/) HDMI output + Transputer FPGA emulation </br>

[Atari ATW800](https://en.wikipedia.org/wiki/Atari_Transputer_Workstation) was a complete architecture re-design, that included a standard Atari ST as helper machine. </br>
had a Transputer CPU = optimized for Parallel processing, similar to GPU's today & HMB memory. </br>
with its own operating system, and developer SDK, Not compatible with standard C and ASM. </br>

[ATW800/2](https://www.geekdot.com/atw800_2/) is a recreation board in FPGA, giving HDMI output + 1x Transputer CPU to a TT 030 or MegaST machine. </br>

[ST2VGA](https://sidecartridge.com/products/st2vga-atari-st/) & [TenoxVGA](https://www.legacypixels.com/atari/ecl2vga.html) [pcbway](https://www.pcbway.com/project/shareproject/TenoxVGA___ECL2VGA_Adapter_for_Atari_TT_High_Res_Mode.html) [github](https://github.com/tenox7/tenoxvga) = Many Flicker Fixer options for Amiga DB23 port. </br>
Atari ATW800/2 = zz9000 on the Amiga or similat PicassoIV.. </br>

Amiga was aiming at a higher Desktop Workstation Profesional Environment, </br>
because [NASA used several Amigas](https://www.youtube.com/watch?v=ZxW3E7UMrKM&t=91s) for Telemetry data display. </br>
Atari was focused on "All-In-One" Keyboard sollution & Gaming console. </br>
Apple during the Pepsi-CEO era refused to help NASA, according to NASA. </br>
NASA never mentions Atari, probably because Atari was rare in US, mostly European costumers. </br>
with few Musician exeptions because MIDI ports. </br>

Apple had ProTools TDM DSP audio, because the NuBus, also a small MIDI market. </br>
Atari had the MIDI market, becasue the built-it MIDI ports. </br>
Amiga had an alternate Midi Tracker market, video Editing market "Toaster", 3D graphics like Babilon TV series. </br>

There was a "Pacman" type game for Atari, allowed to interconnect upto 16x Atari ST using midi ports, like a Ring Network. </br>
Revolutionary. </br>
similar [DOOM v1.1 for DOS](https://www.youtube.com/watch?v=q3NQQ7bPf6U) allowed 3x PC's for Triple displays, </br>
option was removed in next versions. </br>

Atari STE games had nice graphics, maybe similar to Amiga AGA. </br>

Atari built-in MIDI I/O ports was "Ready for Musicians" </br>
MIDI ports are the same in All Atari ST / Mega / TT / Falcon variants, based on the ACIA M6850p </br>

Amiga has MIDI with optional 3rd party Serial to Midi dongles, some are very different from others. </br>
Full version of Cubase was never ported to AmigaOS, only TwentyFour "24" "Lite" version, similar to "16" for C64. </br>
Amiga had Bars & Beats, purchaed by Microsoft when developing DirectX, then released as Download. </br>
Amiga also had Octamed & other trackers. </br>

Atari TT has 4x 1MB ROM's running at 8-Bits each = 32-Bits. </br>
Amiga 4000 has 2x ROM's at 16-Bits each. </br>

im surpriced how similar: </br> 
Out of This world game is in all platforms, almost identical in different machines/OS. </br> 

### Floppy & HDD
Lorateck in Poland makes a nice external Ultra SD drive. </br>

### Links: </br>
https://atari.joska.no/snapshots/freemint/cpu/ </br>
https://freemint.github.io/tos.hyp/en/index.html </br>
https://gtello.pages-perso.free.fr/downld_e.htm </br>
https://freemint.github.io/ </br>
https://www.muzines.co.uk/articles/micromidi/6021 </br>
https://www.best-electronics-ca.com/tt030.html </br>
https://github.com/AtarianComputing/Atari-TT030-PCB </br>

### HW inside
https://www.atarimuseum.de/tt030.htm </br>
https://www.fplanque.com/tech/retro/atari/atari-falcon-inside-and-out/ </br>

### CT060 CPU accelerator
counterpart of Amiga variants. </br>
https://gtello.pages-perso.free.fr/falcon_e.htm </br>

### Programming
[Cross-compile Tutorial for TOS](https://web.archive.org/web/20180425224527/http://vincent.riviere.free.fr/soft/m68k-atari-mint/) </br>
by Develper of ["BadMood" Doom version](https://web.archive.org/web/20160318230323if_/http://leonik.net/dml/files/BM307.ZIP) for Atari [Falcon](https://web.archive.org/web/20160318235752if_/http://leonik.net/dml/files/BM307SRC.ZIP) </br>
based on gcc ported tools. </br>
Cygwin for Cross-compiling [TOS on Windows](https://web.archive.org/web/20180425100450/http://www.cygwin.com/) </br>

**Files**
[M68K Atari mint](https://web.archive.org/web/*/http://vincent.riviere.free.fr/soft/m68k-atari-mint/*) </br>

**Documents**
[dev-docs.atariforge.org](https://web.archive.org/web/20171016150036/http://dev-docs.atariforge.org/) </br>

### Forums
https://web.archive.org/web/20180418125841/http://www.atari-forum.com/ </br>

### Atari Unix / Linux
https://web.archive.org/web/20180427081345/http://vincent.riviere.free.fr/soft/m68k-atari-mint/archives/mint/ </br>

AFROS </br>
https://web.archive.org/web/20170825121839/http://aranym.sourceforge.net/afros.html </br>




