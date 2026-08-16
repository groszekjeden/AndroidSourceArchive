# Sources — POCO F3 (alioth)

## ROM

- ROM: LineageOS 20
- Android version: 13
- Device: POCO F3
- Codename: alioth

### Archived Build

- Source: LineageOS Build Archive
- Build page: https://lineage-archive.timschumi.net/build/19487

> The archive page requires JavaScript to display the complete build
> metadata, including filename, checksums, and filesize.

## Device Tree

- Repository: https://github.com/LineageOS/android_device_xiaomi_alioth
- Branch: `lineage-20`
- Android: 13

## Device Tree Dependency

- Repository: https://github.com/LineageOS/android_device_xiaomi_sm8250-common
- Branch: `lineage-20`
- Target path: `device/xiaomi/sm8250-common`

The alioth `lineage.dependencies` file lists this as its direct
device-tree dependency.

## Common Tree Dependencies

The SM8250 common tree should be checked separately for its own
`lineage.dependencies` file. Any repositories listed there are
dependencies of the common tree rather than direct dependencies of
the alioth device tree.

## Kernel

- Repository: https://github.com/LineageOS/android_kernel_xiaomi_sm8250
- Branch: `lineage-20`
- License: GPL-2.0
- Note: Kernel source is not redistributed in this archive.

## Xiaomi Hardware

- Repository: https://github.com/LineageOS/android_hardware_xiaomi
- Branch: `lineage-20`

## Proprietary Files

The device tree contains proprietary-file lists and extraction scripts
for obtaining the required proprietary device files.

The proprietary files themselves are not redistributed in this archive.
They retain their original licenses and copyrights.

## Dependency Chain

```text
android_device_xiaomi_alioth
└── android_device_xiaomi_sm8250-common
    ├── dependencies listed by the common tree
    └── kernel / hardware dependencies as specified upstream
