# Synologist :gear:

Command line system information utility for use with Synology's [Disk Station Manager (DSM)](https://www.synology.com/en-us/dsm).

Approximates select output of Synology's [Info Center](https://kb.synology.com/en-vn/DSM/help/DSM/AdminCenter/system_info_center?version=7).

## Sample Output 

	--------------------
	Basic Information
	--------------------

	Server name: SYNOLOGIST
	DSM version: 7.1.1

	--------------------
	Hardware
	--------------------

	Serial number: 1760P5M096007
	Model name: RS18017xs+
	CPU: Intel(R) Xeon(R) CPU D-1531 @ 2.20GHz
	Total physical memory: 31.1293 gB

	--------------------
	Network
	--------------------

	Ethernet stats (all):
	eth0: 00:11:32:79:95:1b 169.254.21.82/16
	eth1: 00:11:32:79:95:1c 169.254.105.132/16
	eth2: 00:11:32:79:95:1d 169.254.69.117/16
	eth3: 00:11:32:79:95:1e 169.254.206.44/16
	eth4: 00:11:32:79:95:1f 172.22.115.222/23
	eth5: 00:11:32:79:95:20 169.254.4.191/16

	Network stats (active):
	eth4: 00:11:32:79:95:1f 172.22.115.222/23
	eth5: 00:11:32:79:95:20 169.254.4.191/16

	--------------------
	Time
	--------------------

	System time: 10:45:56
	Uptime: 128 days 11:27

	--------------------
	Storage
	--------------------

	Volume(s):
	Name     Used% Used Total
	/volume1 48% 75T 158T
	/volume2 34% 54T 158T
	/volume3 47% 73T 158T
	/volume4 75% 78T 105T

## "Supported" Synology Models (i.e. tested to run on the following)

|Model #    |
|---        |
|DS212j-j   |        
|DS1515+-j  |
|DS1517+    |
|DS1517+-j  |
|DS1621+    |
|DS1817+-j  |
|DS1819+    |
|DS2419+    |
|DS3622xs+  |
|DS416play-j|
|RS815rp+-j |
|RS18017xs+ |
|RS3621xs+  |
|SA3400     |

## Getting Started

__Liftoff:__

Make this script accessible to all users by placing it in: `/usr/local/bin`;

set the executable bit on the file:

`sudo chmod +r synologist`;

then call it:

`bash synologist`.

## History

| Version| Relase Date|
| ---    | ---        |
| v.0.0  |04-FEB-2023 |

## License

[LICENSE](https://github.com/marshki/synologist/blob/master/LICENSE)
