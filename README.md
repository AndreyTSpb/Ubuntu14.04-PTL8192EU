# Ubuntu14.04-PTL8192EU
Driver add to Ubuntu 14.04.

sudo apt-get install git
git clone https://github.com/Mange/rtl8192eu-linux-driver.git
cd rtl8192eu-linux-driver
make
sudo make install
sudo modprobe 8192eu
