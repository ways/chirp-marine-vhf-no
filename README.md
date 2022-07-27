# CSV files for CHIRP

Tested with Baofeng.


## marine_vhf.csv

marine_vhf.csv is an improved Chirp (http://chirp.danplanet.com/projects/chirp/wiki/Home) file for VHF marine channels. Stock "Marine VHF channels" did not match marine channel numbers with baofeng channel numbers. Fixing with Kanalbruk.htm from http://trudelutt.com/linker/vhf_kanaler_nor.htm as source.

I'm not sure where L and F channels are usually placed, or which countries use them, so I put them at 30-35 to "save" memory slots. Let me know if there's a standard numeric location for them.

Also removed all Skip flags, as I'd like all channels to be scanned. Open for input on which are pointless to scan (like AIS?).

TODO:
* Check if Chirp wants to use this as new generic maritime config: http://chirp.danplanet.com/issues/3853


## norway_ruter.csv

http://ruter.no. norway_ruter.csv is the internal comms for Oslo, Norway bus, tram and metro. Some channels have been migrated to TETRA (encrypted), but others remain active.


## hunt-norway.csv

Hunting radio (jaktradio). Source: http://frekvenser.no/Jaktradio.html#vis_frekvenser


## hunt-sweden.csv

Hunting radio (jaktradio). Only 15x MHz band, not 3x MHz as I don't have a radio to test them. Source: http://frekvenser.no/Jaktradio.html#vis_frekvenser

## security-norway.csv

Sikringsradio for Norway. Source: http://www.jegerservice.com/filer/pdf/frekvenser_jakt_sanke_sikringsradio.pdf

## kdr-444.csv

https://en.wikipedia.org/wiki/KDR_444

## pmr-446.csv

Analog channels only: https://no.wikipedia.org/wiki/PMR446

## repeaters-norway-*.csv

Repeaters from https://www.nrrl.no/repeaterkart
