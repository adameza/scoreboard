Component	Updated Specification	Qty	Notes
RGB LED Matrix Panels	128x64 HUB75 / HUB75E (P2.5 pitch recommended)	4	Yields a 512x64 resolution (~4 feet / 1.28 meters wide).
5V Power Supply	5V 20A (100W) (e.g., Mean Well LRS-100-5)	1	Bumps capacity up from 15A to 20A to cover peak brightness across 32,768 LEDs plus the Pi.
Panel Power Cables	4-pin Spade-to-VH3.96 power cables	4	Typically included with each panel purchase.
Data Ribbon Cables	16-pin IDC HUB75 ribbon cables	4	1 for Bonnet-to-Panel 1, and 3 for panel-to-panel daisy chaining.
Main Power Cabling	12 AWG or 14 AWG stranded copper wire	~6 ft	Thicker gauge required to safely handle up to 20A from the main power supply output terminals.
Power Distribution Terminal	2-in-8-out Terminal Block / WAGO 221 Lever Nuts	1 set	Cleanly splits the single high-amperage output from the PSU into 5 individual power legs (4 panels + Pi).
Raspberry Pi Controller	Raspberry Pi 3B+, 4B, or 5	1	Remained unchanged.
Matrix HAT/Bonnet	Adafruit RGB Matrix Bonnet / HAT	1	Remained unchanged (requires Address Line E jumper mod).