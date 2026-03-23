4 meg Linux bootfile for USB memory sticks.
This creates a bootable memmory stick, that you then boot off, and will allow you to reset your Windows password. 

Works with Windows 2000, Windows XP, Windows 7, Windows 8, Windows 10 and Windows 11.

Step 1. Extract the ISO files to your computer.  I like to use WinRAR for Windows XP/7.   Windows 10 will automatically read ISO files.

Step 2. Read the README.TXT file within.

Step 3. make a bootable USB drive / key:

a. Copy all files from this CD onto the USB drive.

   It cannot be in a subdirectory on the drive.

   You do not need delete files already on the drive.

   
b. Install the bootloader (you may have to be administrator)
   
   On the USB drive, there should now be a file "syslinux.exe".
   
   Run this from a command line, like this:


	j:\syslinux.exe -ma j:

replace j with some other letter if your USB drive is on another

drive letter than j:

On some drives, you may have to omit the -ma option if you get an error. If it says nothing, it probably did install the bootloader.


Step 4: Ensure that your BIOS is set to boot off a memory stick in the first instance. This is the biggest headache to do.

Step 5: Insert Memory stick. Turn on computer, should boot the small Linux program from off your USB memory stick.

Follow the text menu on the screen to reset your admin and other users passwords. Typically select 'no password' initially.

