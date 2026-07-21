I/O = Input/Output

-  USB(Universal Serial Bus)
	Connecting
	- mouse
	- keyboard
	- pendrive
	- phone
	- webcam
	- printer
	- external SSD

-  USB versions
	- USB 2.0
	- USB 3.x
	- USB4
	the more newer -> the more fast data transmission and bigger performance

-  USB-C
	its a type of USB port
	under can work, USB2, USB3, USB4, Thunderbolt(if its supported)

-  HDMI
	Tasks
	-  VIDEO
	-  AUDIO
	forwarding.
	HDMI ports working if on the motherboards 
	-  CPU have integrated graphic controller 
	-  And its not disabled
	If there is separated GPU the monitor often connect to the GPU HDMI
	or DisplayPort 

-  Display port 
	Same reason like the HDMI
	-  VIDEO
	-  AUDIO
	Its on modern monitors.

-  ETHERNET(RJ45)
	This ensures the wired network
	Linux -> Network Driver -> Ethernet Controller -> RJ45 Port -> Router

-  Audio Jack
	Generally:
	- headset 
	- microphone 
	- speaker
	connection.

-  PS/2
	Old type, for:
	- Keyboard
	- Mouse

-  Thunderbolt
	Its a high speed connection standard
	Its working for:
	-  monitors
	-  external SSDs
	-  docking stations
	-  external GPU
	Lot of thunderbolt are USB-C shaped.

-  Linux view
	USB tools:
	
		 - lsusb
		
	Pcie tools:

		- lspci 

   Network interfaces:

		- ip ling
		- ip addr

-  Cybersecurity view
	USB:
	-  malicious pendrive
	-  keyboard shaped attacking device(BadUSB)
	- firmware manipulations
	ETHERNET:
	- network attack
	- sniffing
	- MITM(Man-in-the-Middle)
	- ARP spoofing
	THUNDERBOLT:
		Bcouse its a high speed and direct contact port
		some systems has a special physical attack surface,
		thats why coorporates environments often regulates the usages of thunderbolt.
	