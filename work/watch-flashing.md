Downdlod and build Heimdall
```
git clone https://gitlab.com/BenjaminDobell/Heimdall
sudo apt install libusb-1.0-0-dev
cd Heimdall
mkdir build
cd build
cmake  -DCMAKE_BUILD_TYPE=Release ..
make -j4
```
Latest firmware for watch
```
http://download.tizen.org/snapshots/tizen/unified/latest/images/standard/wearable-wayland-armv7l-tw2/
```

Download PIT file.
```
sudo  ./heimdall download-pit --output device.pit
```

```
sudo ./heimdall flash --pit device.pit --ROOTFS ./unpacked_tar_gz/rootfs.img --RAMDISK2 ./unpacked_tar_gz/ramdisk-recovery.img --RAMDISK1 ./unpacked_tar_gz/ramdisk.img --SYSTEM-DATA ./unpacked_tar_gz/system-data.img --USER ./unpacked_tar_gz/user.img
```
