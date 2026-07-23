-  CPU main parts
	- Control Unit (CU)
	- ALU (Arithmetic Logic Unit)
	- Registers
	- Cache
	- Bus Interface

-  Control Unit (CU)
	This is the controller of the CPU
	decides:
	- What command next
	- what part should work
	- When read the memory
	- When to write back to memory

-  ALU(Arithmetic Logic Unit)
	This is the calculator 
	- addition, subtraction, multiplication
	- logical operations (OR, IF, NO)
	- comparisons

-  Registers
	The registers are the fastest memory of the CPU
		they are really small, fast
	The ALU typically get the datas from here
		and write back the results.
		(Register A + Register B = Register C)

-  Cache 
	It should store closely the often used datas, so the CPU
	dont have to go always to the RAM.

-  Bus Interface
	Through the Bus Interface, communicating with the:
	- RAM
	- PCIe controllers
	- chipset
	- other hardwares
	Its just move datas.

-  Linux view
	The linux dont making dialogue with the CPU.
	Just using the CPU skills through commands.
	-  Registers 
	-  Interruptions
	-  Command tool set
	-  Cache
	-  multiple seeds