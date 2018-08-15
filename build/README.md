# Build
```
cd Circuit-Sword-Lite/build

chmod +x upgrade-kernel.sh build-image.sh

wget https://github.com/RetroPie/RetroPie-Setup/releases/download/4.4/retropie-4.4-rpi1_zero.img.gz
gunzip retropie-4.4-rpi1_zero.img.gz

sudo ./build-image.sh YES retropie-4.4-rpi1_zero.img.gz
```

Burn resulting .img to SD and boot!
