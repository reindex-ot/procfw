# X-Generation Aftermarket Firmware for Playstation Portable™
PRO Firmware is a Aftermarket Firmware for Playstation Portable™.

It's licensed under the GPLv3, and thus is under full control of the community, made by users for the users.

It will continue to provide you with new features, even after Sony drops the plattform and allows you to develope your own applications for PSP.

Author: Team PRO

# Supported Kernel and Hardware Revisions
- 6.20 [1g, 2g, 3g, 4g, 5g]
- 6.35 [1g, 2g, 3g, 4g, 5g, 7g, 9g]
- 6.39 [1g, 2g, 3g, 4g, 5g, 7g, 9g]
- 6.60 [1g, 2g, 3g, 4g, 5g, 7g, 9g, 11g]

# Detail
SystemControl: kernel of CFW

Rebootex_bin: patch reboot.bin and redirect the loading of bootconfs

Rebootex: load rebootex.bin into kernel and boot the whole CFW

Vshctrl: all VSH related patch goes here. And the ISO VSH dipslay code too.

ISODrivers: march33 and galalxy included for ISO loading

Popcorn: for custom PS1 hack

Installer: install the CFW into the system. After that it can use Rebootex to boot into CFW.

CIPL: permanently install 635PRO on 01g/02g

Satellite: VSH menu

Recovery: Recovery menu as those in 5.XX kernel

testsuite: test tool/homebrews/utils for 635PRO

FastRecovery: Boot the 635PRO faster once installed

include: common used header goes here

libs: common used library goes here

contrib: scripts or else goes here

docs: complex documents goes here

Common: Common code goes here

Imports: The imports of 635 functions go here

# Compile
You need to set $(PRO_HOME) to your source directory

# Credit
### VirtuousFlame
For the ISO Loading Code, Custom PSX EBOOT Support and most of the CFW related code.
### Coldbird
For initial reverse of the TN Kernel Exploit, Hacks to make it 6.3X compatible and several other things CFW related.
### Total_Noob
For the initial discovery of the Power-Kernel-Exploit in 6.20 OFW.
### Mathieulh, Geohotz, TPU and everyone else involved
making PSP signing possible, making the Minna No Sukkiri Exploit redundant.
### Dark_Alex
initial M33 CFW who guided us mentally through several CFW generations by giving good examples on how to patch Sony OFW.
### Davee
v1 register leak address discovery used in Power-Argument-Patching.
victor.rds for the cool animated [Fast Recovery Icon](http://wololo.net/talk/viewtopic.php?f=17&t=3716#p42091).
### Takka and Plum
idea of preventing hibernation deletetion.
### kgsws
idea of faking vshmain module as permanent patch
### bbtgp and Draan
PrxEncrypter source code to produce the signed fake vshmain module for permanent patch
### bbtgp, Dark_AleX, Noobz, Team C+D, M33 Team, and coyotebean
new psardumper source to get the OFW binary
### neur0n
syscall execution in kernel mode, and CIPL allowing hackable PSPs to have CFW installed permanently, and several bug fixes
### jas0nuk
PSPident source to detect if it is a TA-88v3 unit
### ardi
umd4homebrew to enable UMD in homebrews
### some1
exploit on 6.39 OFW, allowing CFW on 6.39
again some1/Davee/Proxima/Zecoxao for their exploit on 6.60 OFW, allowing CFW on 6.60
### Yoti
blocking satellite menu in Go!cam
xFede and sinistro for their translations for Italian and Spanish
### Richard J. Prinz
8x8 fonts in 8x8 Pixel ROM Font Editor
And last but not least - Sony for making a wonderful, however very locked down, portable gaming handheld.
