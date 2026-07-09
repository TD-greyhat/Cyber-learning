##What is Motherboard

- The motherboard(mainboard,system board, logic board)is the central printed circuit board of the computer (printed circuit board - PCB)

- All the important hardwares connect direct to the motherboard
	- CPU - making decisions
	- RAM - workpace
	- GPU - graphic stuffs
	- SSD/HDD - the archive
	- PSU - power tool
	- Network controller
	- USB tools
	
- Main tasks:
	- Connect the hardwares
	 All the data someway flows through on the motherboard.
	 SSD -> <span style="color:rgb(0, 112, 192)">Motherboard </span>-> CPU -> RAM
	- Ensuring communication
	 The motherboard include the <span style="color:rgb(255, 192, 0)">traces </span>where the hardwares communicating through.
     (thin copper wires)
    - Distribute the electric current
	 The PSU - just giving the energy
		but the mainboard handling wich hardware get energy when and how much.
	- Launching(Boot)
	 Power Button -> <span style="color:rgb(0, 112, 192)">Motherboard </span>-> BIOS / UEFI -> CPU -> RAM test -> searching SSD -> OS 
	 -  Expandability
		The motherboard ensures the connectors,
		- PCIe
		- M.2
		- SATA
		- USB
		- Ethernet
		- Audio
		- Fan Headers
		 this is why the computer is expandable.
		 
- Why is it important for Linux learning?
	Linux kernel first should recognize what hardwares are connected,
	to the <span style="color:rgb(0, 112, 192)">motherboard</span>. The firmware(BIOS/UEFI) give the basic informations,
	then the kernel loading the correct drivers, and thats why the CPU, RAM, Memories are useable now.
	
- Why is it important for Cybersecurity?
	Becouse here we can found the
	- Bios/UEFI firmware
	- The TPM (Trusted Platform Module)
	- The base of  the Secure Boot working
	- A lots of hardware security function
	if the firmware has issues, the reinstall the OS isnt working sometimes. 