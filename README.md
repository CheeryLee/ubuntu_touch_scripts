# Ubuntu Touch scripts
There are scripts that you can use for porting Ubuntu Touch to a new device.
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
