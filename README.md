# Compile

```sh
git clone https://github.com/SoloSaravanan/MT7921-Bluetooth-fix.git
cd MT7921-Bluetooth-fix
make
```

# Temporarily add the module

```sh
sudo rmmod btusb.ko
sudo insmod btusb.ko
```

# Permanent Fix

```sh
xz -v btusb.ko
sudo cp btusb.ko.xz /lib/modules/6.9.8-200.fc40.x86_64/kernel/drivers/bluetooth/
```