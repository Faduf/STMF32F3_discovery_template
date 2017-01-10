# STMF32F3 discovery template

##Presentation
This is a template application for the STM32F30x ARM microcontrollers that compiles with gcc_arm_none_eabi compiler. 

Flash this template and see the LEDs of the F3 discovery board turning on and off.

##Source code 
The **src** directory contains the source-code files for this application template.

The **lib** directory contains the standard library files.

##Compiling
This code can be compiled following the steps :
	
	1. Be sure the gcc_arm_none_eabi compiler is installed. The following commands can be used :

	sudo apt-get remove binutils-arm-none-eabi gcc-arm-none-eabi
	sudo add-apt-repository ppa:team-gcc-arm-embedded/ppa
	sudo apt-get update
	
	2. Open a terminal and enter the directory
	3. Enter the command line "make" in the terminal
	4. A folder obj should appear with the .bin file to flash the target
