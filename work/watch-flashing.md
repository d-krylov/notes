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
