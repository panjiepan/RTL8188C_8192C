# RTL8188C_8192C
The linux driver of RTL8188C_8192C with dkms support.

This is the ubuntu 16.04 linux driver for a usb wifi dongle (with antenna) bought from tabao.com .

This driver has removed the /proc file support because from linux kernel 3.10 the VFS is not compatible with old 'proc' system calls. You can check the source code in 'os_dep/linux/os_intfs.c' for that.
