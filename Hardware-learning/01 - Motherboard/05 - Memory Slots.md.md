-  What is a Memory slot?
	The memory slot (DIMM slot) its on the motherboard,
	this is where we place the RAMs.
	
	The CPU use this to temporarily read the datas.

-  What is DIMM?
	**Dual Inline Memory Module**
	This is the standard for PCs.
	Laptop use smaller **SO-DIMM**
	
- Why there is more RAM slots?
	Most motherboard have 2-4.
	- more maximum memory
	- easy expandability 
	- utilization of more memory channel.

- What is the Memory Channel?
	This is the data channels between the CPU and the RAMs.
	- Single channel: CPU <-> RAM (one way)
	- Dual channel:    RAM(a) <-> CPU <-> RAM(b)
	More data can move at the same time.

- Why is it important where to place the RAMs?
	Mainly we place(if we have 2) int to A2 and B2 slot.

	if you place it in to a wrong slot, maybe the system will 
	not find the dual channel mod.

- Slot differences?
	- DDR4 RAM -> DDR 4 slot
	- DDR5 RAM -> DDR 5 slot
	there is physical differences. 
	In RAM modul there is a physical kerf (notch) that handling compatibility. 

- Quantity of the RAMs?
	- based on the motherboard
	- CPU memorycontroll
	- RAM generations
	32 GB - 192 GB or more

- Linux perspective
	Under Linux the kernel recognize:
	- How many RAM module we have
	- Which slot has RAM
	- How much the capacity
	- What speed on they are working
	
	Usefull commands:
	
		- free -h
		- cat /proc/meminfo
		- sudo dmidecode --type memory

-  Cybersecurity perspective
	- sensitive data like (passwords, key) it can be temporary in the RAM.
	- attacks like memory reading use this place
	- system stability and reliability depends on 
	