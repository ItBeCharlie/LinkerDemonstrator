# LinkerDemonstrator

This repo contains 3 executables for demonstrating how LCC object modules are linked.

"lwin" is executable on Windows devices
"lintel" is executable on the old Intel chip Macs
"larm" is executable on the new M1 and M2 chip Macs

To use, link files as you would with the lcc. For example,
lcc startup.o m1.o m2.o
will link the three object files and describe the process.
