# ENEE447 Project 0
## Files to modify:
- `time.c`

## Recommended Readings 
- [ARMv8 Peripherals Manual (Page 172)](https://myelms.umd.edu/courses/1277187/files/folder/Lab%20Files%20Spring%202020/ARMv8%20Documentation?preview=55360007)
- [Bare metal programming](https://github.com/dwelch67/raspberrypi/tree/master/baremetal)
- [How Raspberry Pi boots](https://raspberrypi.stackexchange.com/questions/10442/what-is-the-boot-sequence)
- [Connecting an SD card to an Ubuntu VM](https://pubs.vmware.com/workstation-11/index.jsp?topic=%2Fcom.vmware.ws.using.doc%2FGUID-AB5C80FE-9B8A-4899-8186-3DB8201B1758.html)
- [Connecting an SD card to an Ubuntu VM 2 (Look at the answer with 68 upvotes)](https://askubuntu.com/questions/29284/how-do-i-mount-shared-folders-in-ubuntu-using-vmware-tools)

## Environment Setup
- See p0.pdf for cross-compiler setup instructions
- Add the /bin folder of the cross-compiler to your PATH. This may require you to add the PATH modification command to your home .bashrc file
- SD card: Format single FAT32 partition named "boot"
  
## Develop & Test
- Copy the files (not the folder) in SD Files folder to your SD card 
- Compile your code with `make cp` command (may need to modify the "cp" line in the Makefile to reflect the path to your SD card) 
- Boot your Raspberry 3B+ with the SD card. Should see 7 fast blinks of the green activity LED if boot was successful - does not mean your timer code is correct)
- The activity LED should blink with frequency 1 Hz

