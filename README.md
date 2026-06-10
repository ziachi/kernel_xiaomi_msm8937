# Kernel — Xiaomi MSM8937 (santoni)

Linux kernel 4.9.227 for Xiaomi Redmi 4X (santoni) — used in Matrixx 15 (Android 15) build.

## Info

| Detail | Value |
|--------|-------|
| Kernel version | 4.9.227 |
| Defconfig | `santoni_treble_defconfig` (725 lines) |
| Architecture | ARM64 |
| SoC | Qualcomm MSM8937 (Snapdragon 430) |
| Branch | `matrixx-15` |
| Path | `kernel/xiaomi/msm8937` |
| Files | 62095 |

## Usage

This repo is automatically pulled by the device tree via `lineage.dependencies` or `local_manifests`.

```bash
git clone https://github.com/ziachi/kernel_xiaomi_msm8937 -b matrixx-15 kernel/xiaomi/msm8937
```

## v3 Changes
- Performance-tuned defconfig for santoni 2GB RAM
- Treble-compatible configuration

## Related Repos
- [Device tree](https://github.com/ziachi/device_xiaomi_santoni/tree/matrixx-15)
- [Vendor blobs](https://github.com/ziachi/vendor_xiaomi_santoni/tree/matrixx-15)

---

## Thanks To
- [androidsantoni](https://github.com/androidsantoni/kernel_xiaomi_msm8937) — kernel base
- [omansh-krishn](https://github.com/omansh-krishn) — thanks for keeping the source alive
- [LineageOS](https://github.com/LineageOS/android_kernel_xiaomi_msm8937) — kernel upstream maintainer
