-  The VRM(Voltage Regulator Module) 
	PSU -> Motherboard -> VRM -> CPU
	The VRM prapare the energy to the CPU.
	-  Quantity, make sure the stability, tracking CPU requirements.
	-  Better CPU requires better Motherboard, bcouse of the tunings, and overclocking.

-  Parts of the VRM
	-  MOSFETs
	-  Chokes (induktorok)
	-  Capacitors (kondenzatorok)
	-  PWM controller

-  VRM Phases
	The more Phases there is, make easier to distribute energy.
	ex: 14+1+1 Phase or 8+2 Phase
	-  Lower heat
	-  stabile working
	-  Better performance under heavy load
	
-  Linux view
	There is no direct user usages for the VRM
	but you can see the
	-  CPU clock signal changing
	-  Heat
	-  Energy usage
	-  Thottling
	
	Useful commands:
	
		- lscpu
		- cat /sys/devices/system/cpu/cpu*/cpufreq/scaling_cur_freq

Some hardware has their own VRM like the GPU, SSDs.