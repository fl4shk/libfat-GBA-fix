# libfat-GBA-fix
The latest version of libFAT for the GBA appears to be not working, and
requires a small fix.  A test program is included.

I am somewhat annoyed that I can't use libFAT in GBA emulators.

Note that devkitARM is required for this program to build properly.  After
the GBA ROM is built, it needs to be DLDI patched for the flash cart on
which you want to run the program.  The DLDI for the EZ Flash IV is
included with the filename ezsd.dldi.
