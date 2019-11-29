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
