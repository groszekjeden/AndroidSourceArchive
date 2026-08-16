# Sources — POCO F3 (alioth)

## ROM

- ROM: LineageOS 23.2
- Android version: 16
- Device: POCO F3
- Codename: alioth

## Device Tree

- Repository: https://github.com/LineageOS/android_device_xiaomi_alioth
- Branch: `lineage-23.2`
- Android: 16

## Device Tree Dependency

- Repository: https://github.com/LineageOS/android_device_xiaomi_sm8250-common
- Branch: `lineage-23.2`
- Target path: `device/xiaomi/sm8250-common`

The alioth `lineage.dependencies` file lists this as its direct
device-tree dependency. 0

## Common Tree Dependencies

### Xiaomi Hardware

- Repository: https://github.com/LineageOS/android_hardware_xiaomi
- Branch: `lineage-23.2`
- Target path: `hardware/xiaomi`

### Kernel

- Repository: https://github.com/LineageOS/android_kernel_xiaomi_sm8250
- Branch: `lineage-23.2`
- Target path: `kernel/xiaomi/sm8250`
- License: GPL-2.0

The kernel source is not redistributed in this archive. The upstream
repository is provided for source provenance.

The SM8250 common tree lists both the Xiaomi hardware repository and
the SM8250 kernel as dependencies. 1

## Proprietary Files

The device tree contains proprietary-file lists and extraction scripts
for obtaining the required proprietary device files.

The proprietary files themselves are not redistributed in this archive.
They retain their original licenses and copyrights.

## Dependency Chain

```text
android_device_xiaomi_alioth
└── android_device_xiaomi_sm8250-common
    ├── android_hardware_xiaomi
    └── android_kernel_xiaomi_sm8250
