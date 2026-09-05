# Changelog — klee (OrangeFox)

Range: **2026-08-20** to **2026-09-05** (by commit date)
Total: 47 commits

---

## 2026-09-05

- **recovery:** partitionmanager: skip free-space refresh during active sideload/update_engine install _(picked from claude)_
- **recovery:** recovery: Fixup [1/2]

## 2026-09-04

- **recovery:** minuitwrp: bypass GGL blit for RGB565 screenshot capture
- **recovery:** minuitwrp: Sync gr_color() R/B swap with RGB_565 format table
- **recovery:** libpixelflinger: Swap R/B channel bit positions for RGB_565
- **recovery:** minuitwrp: Fix screenshot heap overflow on non-32bpp surfaces
- **recovery:** minuitwrp: Fix RGB_565 blank screen by syncing DRM format with base_format

## 2026-09-03

- **device:** klee: Switch pixel format to `RGB_565`
- **device:** Revert "klee: Auto-start `touch_report` HAL on boot in recovery"
- **device:** klee: Correct remkte

## 2026-09-02

- **device:** klee: Use our fork repo auto sync instead of manual sync
- **recovery:** recovery: Adapt for POCO X8 Pro / REDMI Turbo 5 (klee)
- **core:** libfs_avb: Allow LKs patched with fenrir to boot on AOSP _(picked from Mashopy)_

## 2026-09-01

- **device:** klee: Force periodic re-flip on idle to avoid DSI buffer underrun flicker
- **device:** klee: Fallback to lazy unmount for /vendor on EBUSY

## 2026-08-27

- **device:** klee: Fix vendor_boot cache/flash on custom kernel with baseband_guard
- **device:** Revert "klee: Drop /odm/firmware/ from firmware_directories"
- **device:** klee: Use prebuilt `libklee_libcxx_compat.so` for keymint service
- **device:** klee: Retry format data after metadata wipe on merge-status failure

## 2026-08-26

- **device:** klee: Allow choosing runner for build job
- **device:** klee: Auto-start `touch_report` HAL on boot in recovery

## 2026-08-25

- **device:** klee: Switch runner to `ubuntu-24.04`
- **device:** klee: Cut load-haptic-modules boot delay from 20s to 1s
- **device:** klee: Drop `com.android.media.swcodec.apex` from loadApexImages
- **device:** klee: klee: Always return to `fox_14.1` instead of `broken repo`

## 2026-08-24

- **device:** klee: Document tree layout and GitHub Actions build flow
- **device:** klee: Group config files by function and add section docs
- **device:** klee: Move first-party sources into src/
- **device:** klee: Consolidate helper scripts into tools/

## 2026-08-23

- **device:** klee: Fallback to lazy unmount for /odm on EBUSY
- **device:** klee: Add support for ICS haptics
- **device:** klee: Add embedded weaver for Global ROM

## 2026-08-22

- **device:** klee: Drop Unmap_Super_Devices() from Check_Pending_Merges
- **device:** klee: Drop /odm/firmware/ from firmware_directories
- **device:** klee: Add support for AWINIC haptics
- **device:** klee: Adjust status bar item position

## 2026-08-21

- **device:** klee: Add github compiler script
- **device:** klee: Use official MTK AIDL boot HAL to fix boot-slot switching
- **device:** klee: Embedded software Weaver fallback for FBE decrypt
- **device:** klee: Create bootdevice symlink
- **device:** klee: Fix some logical partition mounts fail _(picked from woshimaniubi8)_
- **device:** klee: Remove AVB parameters from fstab.mt6899 _(picked from Kaze)_
- **device:** klee: Drop USB Offload from DTB
- **device:** klee: Add source patches into tree

## 2026-08-20

- **device:** klee: Add GPLv3 license headers to source files
- **device:** klee: Add device info on README.md
- **device:** [SQUASH]: klee: OrangeFox Recovery Project Bringup
- **device:** klee: Initial twrp device tree _(picked from Byben)_
