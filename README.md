# Tools

> Tools of the trade

## General

+ Good Linux machine or VM either via VMware, VirtualBox, or vagrant - would suggest Ubuntu 14.04 LTS
+ Python (both 2.7 and 3)
+ Hex Editor (ghex recommended)

## Binary exploitation/reversing

+ [IDA](https://www.hex-rays.com/products/ida/index.shtml) (Demo, if not Pro)
+ [gdb](https://www.gnu.org/software/gdb)
+ [PEDA](https://github.com/longld/peda) - makes gdb far more usable
+ [qira](http://qira.me/) - if you can get it to work & understand it
+ [checksec](https://github.com/slimm609/checksec.sh) - peda can give the same info though
+ [pwntools](https://pwntools.readthedocs.io/en/stable/) makes pwning easier
+ [radare2](https://github.com/radare/radare2) - reverse engineering framework
+ [angr](https://github.com/angr/angr) - a binary analysis framework with a great symbolic execution engine
+ [fupy](https://github.com/gdelugre/fupy) - fast and dirty python decompiler

## Cryptography

+ [Rumkin ciphers](http://rumkin.com/tools/cipher/) - multiple (ancient) crypto stuff
+ [quipqiup](http://quipqiup.com/) - solving cryptograms
+ [xortool](https://github.com/hellman/xortool) - solving multi-byte xor cipher
+ [rsatool](https://github.com/ius/rsatool) - to calculate rsa params

## Forensics
+ [Foremost](http://foremost.sourceforge.net/) - recover hidden files
+ [Binwalk](https://github.com/devttys0/binwalk) - find offsets of files which are concatenated contiguously
+ [Autopsy](https://github.com/sleuthkit/autopsy) - find deleted files from harddisk dumps
+ [Wireshark](https://wireshark.org) - analyze network captures
+ [Stegsolve](http://www.ww.caesum.com/handbook/Stegsolve.jar)

## Web exploitation
+ [GitTools](https://github.com/internetwache/GitTools) - downloads exposed .git repo of vulnearable websites
+ [SQLMap](https://github.com/sqlmapproject/sqlmap) - automated sql injection
+ [Hackbar](https://addons.mozilla.org/en-US/firefox/addon/hackbar/) - indispensible addon for web exploitation in firefox
+ [CookieManager](https://addons.mozilla.org/en-US/firefox/addon/cookies-manager-plus/) - addon for firefox