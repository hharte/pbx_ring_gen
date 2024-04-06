# PBX Ring Generator

This project is a small carrier board for the Power DSine [PCR-SIN06V24F00](https://www.microsemi.com/document-portal/doc_view/10615-pcr-sin06series-datasheet) 4W Ring Generator.  It takes -24VDC as input and supplies isolated 86Vrms / 20Hz ringing current at 4 REN.

Stuffing options are provided for DC-biasing the output.

The board is 1.75”H x 3.93”W for mounting on a 2” relay panel such as the [WE 755A PBX Power Supply](https://github.com/hharte/we755a_ps).

![alt_text](https://raw.githubusercontent.com/hharte/pbx_ring_gen/main/doc/pbx_ring_gen_w_cover.jpg "image_tooltip")

![alt_text](https://raw.githubusercontent.com/hharte/pbx_ring_gen/main/doc/pbx_ring_gen_top.jpg "image_tooltip")

![alt_text](https://raw.githubusercontent.com/hharte/pbx_ring_gen/main/doc/pbx_ring_gen_bottom.jpg "image_tooltip")


# Hardware


## PC Board Bill of Materials

[Interactive BOM](https://html-preview.github.io/?url=https://github.com/hharte/pbx_ring_gen/blob/main/hardware/bom/ibom.html)

[Digi-Key Parts List](https://www.digikey.com/en/mylists/list/BBLJD8V3Z4)


## Cover

A 3D-printed cover is included.  [For safety](https://en.wikipedia.org/wiki/UL_94), it’s a good idea to print this using [V-0 PETG](https://prusament.com/materials/prusament-petg-v0/). To mount the board with cover, use 4ea M3-10mm male/female standoffs for the bottom side of the board.  Use 4ea M3-20mm female standoffs for the top side of the board.  Mount the cover with 4ea M3 screws.


# References


* [PCR-SIN06V24F00 Datasheet](https://www.microsemi.com/document-portal/doc_view/10615-pcr-sin06series-datasheet)
* [Telephone Ring Voltage Tech Bulletin](https://www.sandman.com/knowledgebase/ring-voltage-tech-bulletin)
