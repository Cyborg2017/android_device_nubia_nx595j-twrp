# android_device_nubia_nx595j
Tree for building TWRP for Nubia Z17S

## Kernel Sources

https://github.com/Cyborg2017/android_kernel_nubia_msm8998-oss/tree/lineage-20.0

## To compile

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_nx595j-eng

mka adbd recoveryimage

## Device specifications

ZTE Nubia Z17S (codenamed "nx595j") is a high-range smartphone from Nubia.
It was released in June 2017.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 2.45 GHz Kryo 280 & Quad-core 1.9 GHz Kryo 280
Chipset | Qualcomm MSM8998 Snapdragon 835
GPU     | Adreno 540
Memory  | 6/8 GB RAM
Android Version | 7.1.1
Storage | 64/128 GB
Battery | Li-Ion 3200mAh battery
Display | 1080 x 1920 pixels, 5.5 inches
Back camera  | Dual 23/12 MP, f/1.8, phase detection autofocus, dual-LED (dual tone) flash
