# Yocto 2.2-r2.2 for Digi ConnectCore6UL Starter Kit Single Board Computer.

The main reason of this repository is to post the new compiled version of OS Yocto 2.2-r2.2 fully operational for SBC model ConnectCore6UL because originally it has Yocto compiled in version 2.0.

Additionaly you can find already installed the utilities:
- nano
- e2fsprogrs
- i2c-tools
- lighttpd
- glibc-staticdev
- openssh-sftp-server
- ruby
- gdb
- gdbserver

Next steps are uncompress the files in a uSD (in a FAT16 partition), insert it in the module and reboot using U-Boot to install the new version of Yocto. Execute "run install_linux_fw_sd".

If you have any question please send me an e-Mail to info@homebrain.com.ar.

### Antonio Rodríguez
