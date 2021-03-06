# Ubuntu Touch scripts
There are scripts that you can use for porting Ubuntu Touch to a new device.

**[UPD 10.07.2017]:** Due to the fact that Canonical ceased to support OS, the scripts are irrelevant. However, they can be used as a base for developing new scripts.

## rootstock_touch_install
This script is taken from Launchpad repository. It allows you to write a system image on your device.
#### How to use:
``` 
rootstock_touch_install ubuntu_tarball.tar.gz system.img 
```
- `ubuntu_tarball.tar.gz` — main system tarball in tar.gz that you can download from Ubuntu's site.
- `system.img` — a special system image for your device. If your device is officialy supported, you can download this image from Ubuntu's site. If not, you need to build it yourself.

## check_program_version
This script was written to introduce support for Linux older than 3.4. It shows the programs that are not supported by old kernels.
#### How to use:
```
check_program_version path_to_tarball
```
- `path_to_tarball` — path to unpacked system tarball in tar.gz that you can download from Ubuntu's site.

## build_on_archlinux
The script downloads and installs all required dependencies for the successfull Ubuntu Touch building on your ArchLinux.
#### How to use:
```
build_on_archlinux download path_to_download
```
- `path_to_download` — path where you want to store the source code.
