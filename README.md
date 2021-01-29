# robot_udev for Ubuntu 18.04

udev rule creator for robot.

## Install Libraries Udev for python
```
$ sudo apt install python-gobject
$ sudo apt install libtool-bin
$ sudo apt install python-gobject-2-dev
$ sudo apt install autoconf
$ sudo apt-get install libgudev-1.0-dev
$ rm -rf python-gudev
$ git clone https://github.com/nzjrs/python-gudev.git
$ cd python-gudev
$ ./autogen.sh 
$ make
$ sudo make install
```

## Creating udev rule
1. Run the udev creator:
```
$ rosrun robot_udev robot_udev.py
```

2. after setup udev rules check by:
```
$ ls /dev
```
