# GRAINS-O2Minipops
Jan Ostman's O2 Minipops for AE Modular GRAINS

The original code was published here:
https://janostman.wordpress.com/the-o2-source-code/

Jan Ostman's website is not available anymore. But the code can be found using the wayback machine
on archive.org: https://web.archive.org/web/20170107051059/https://janostman.wordpress.com/the-o2-source-code/

## Changes
There is a clock signal on output D of the AE Modular GRAINS. This can be used for example to synchronize the AE Modular SEQ8 to the GRAINS-O2Minipops.

## Limitations
There is a problem reading values from A0 to A3 of the GRAINS module. So right now only A4 is usable. A4 is used to change the tempo. The pattern is fixed. The variable `patselect` is set to 1. You can change the pattern in line 762.

## References
Wikipedia page of the original Korg Mini Pops
https://en.wikipedia.org/wiki/Korg_Mini_Pops

The GRAINS wiki page
https://wiki.aemodular.com/pmwiki.php/AeManual/GRAINS

The GRAINS module in the Tangible Waves Shop
https://www.tangiblewaves.com/store/p86/GRAINS.html
