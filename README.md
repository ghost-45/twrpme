Umidigi Devices Repository
==========================

The Umidigi S3-Pro (codenamed _"S3-Pro"_) is a flagship smartphone from Umidigi.

It was announced on 25 December 2015.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 2.0GHz Octa-Core MT6755 (Helio P10)
GPU     | Mali-T860
Memory  | 4GB RAM
Shipped Android Version | 6.0
Storage | 32GB
Battery | 3000 mAh
Display | 5.5" 1920 x 1080 px
Rear Camera | 13MP (Sony IMX258 Exmor RS), Dual LED Flash, Laser autofocus
Front Camera | 8MP (OV)

![Ulefone Devices](https://lh6.googleusercontent.com/14LQr0O-Maf5QWqGh1rlj6gM1W8B6tj-EFe8gQrLW4ujGYTBc6aY_zp66-BAXXm0nPEpvujv1vhYdIT_P8ipArBwskxgBUBCvS-fJ2h1dhDrYVoBeL1oZ9cBpkAcmDz8qahpuRIK "Umidigi S3-Pro in black")

This branch is for building TWRP.

### Thanks to:
 * CyanogenMod team
 * Deepflex
 * Wuxianlin
 * Ferhung
 * SHVED
 * Xen0n
 * JonnyXDA
 * olegsvs
 * Visi0nary
 * andyrichardson
 * Team M.A.D

### To build: 
```
repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_lineageos.git -b twrp-14.1

repo sync

. build/envsetup.sh

lunch lineage_p9000-userdebug

make clean && make recoveryimage
```

