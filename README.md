# Compile

```sh
git clone https://github.com/SoloSaravanan/MT7921-Bluetooth-fix.git
cd MT7921-Bluetooth-fix
make
```

# Add module

```sh
sudo rmmod btusb.ko
sudo insmod btusb.ko
```