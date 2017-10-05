xv6 port for ARMv7-A
====================

Please read the README file for an overview of the project.

This branch (rpi2) targets the Raspberry Pi 2 and 3 in 32-bit AArch32 mode.

To compile the xv6 port on x86_64 hosts try:

	make loader target=rpi2

On RPI board it is just:

	make loader 

There is also a FVP target in Makefile for ARM Cortex-A9 part of ARM DS-5 development environment. The FVP port is not complete, but it's nice to see the startup code in a debugger.

Please note you have to copy the config.txt file beside the kernel image to the boot directory. 

Have fun,
Mahdi Amiri K.
