# USB-C-Li-Ion-Charger-Module

Specs
	
Input	USB-C, 5 V

Battery	1-cell Li-ion, 3.7 V nominal 

Charger	TI BQ24074 (linear charger with power-path management)

Boost	TI TPS61088 synchronous boost

Output 5.1 V regulated

Board	2-layer  

The BQ24074 feeds the system rail and charges the battery at the same time, so the board would keep running from the USB while the battery charges and switches to the battery once the USB is unplugged. The system then feeds into the TPS61088 which steps it up to 5.1V output.
