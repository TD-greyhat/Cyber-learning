Its a battery on the motherboard, when the computer is off, its still wroking.
-  save BIOS/UEFI settings
-  operate a Real TIme Clock(RTC)
On modern motherboards the BIOS firmware itself is in a flash memory
(so did not lost when the battery run out of power)

-  What is the RTC?
	RTC = Real Time Clock 
	- storing date, and time
	- follow real time
	using the energy of the CMOS battery

-  Whats happening if it turn off?
	- BIOS settings can turn back to the basics
	- Time and date can be incorrect
	- Boot order changing
	- Maybe error messages

-  Why time is important?
	If the time is incorrect
	- SSL/TLS certificates can be faulty
	- logs dates can be faulty
	- time based authentications (TOTP codes) can be problematic

-  Clear CMOS
	BIOS/UEFI settings can restore to deafult
	- with jumper
	- button(with some motherboards)
	- or with the buttery temporarly removal

-  Linux view 
	The Linux queries the hardware clocker.
	commands:

		 - timedatectl
		 - hwclock

-  Cybersecurity view
	- log analisys
	- digital signature
	- Kerberos authentication
	- TLS certificates
	- incident investigation
	If the time wrong, a lot of system can operate badly.