# Android Kernel — Samsung Galaxy A12s (SM-A127F/DS)

| Field | Value |
|---|---|
| Device | Samsung Galaxy A12s (SM-A127F/DS) |
| Codename | a12s |
| SoC | Exynos 850 (s5e3830) |
| Android version | 13 |
| Defconfig | exynos850-a12snsxx_defconfig |
| Branch | lineage-21 |

## Source
Extracted from Samsung Open Source Release (OSS) package:
`SM-A127F_SWA_13_Opensource.zip`

## Building
```bash
export ARCH=arm64
export CROSS_COMPILE=aarch64-linux-android-
make exynos850-a12snsxx_defconfig
make -j$(nproc) Image
```
