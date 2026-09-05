# Changelog — klee (OrangeFox)

From: **2026-08-20** to **2026-09-05**
Total: 48 commits

---

## 2026-08-20

- **device:** klee: Initial twrp device tree _(picked from Byben)_
- **device:** klee: Add GPLv3 license headers to source files
- **device:** klee: Add device info on README.md
- **device:** [SQUASH]: klee: OrangeFox Recovery Project Bringup

## 2026-08-21

- **device:** klee: Add source patches into tree
- **device:** klee: Drop USB Offload from DTB
- **device:** klee: Create bootdevice symlink
- **device:** klee: Fix some logical partition mounts fail _(picked from woshimaniubi8)_
- **device:** klee: Remove AVB parameters from fstab.mt6899 _(picked from Kaze)_
- **device:** klee: Embedded software Weaver fallback for FBE decrypt
- **device:** klee: Use official MTK AIDL boot HAL to fix boot-slot switching
- **device:** klee: Add github compiler script

## 2026-08-22

- **device:** klee: Adjust status bar item position
- **device:** klee: Add support for AWINIC haptics
- **device:** klee: Drop /odm/firmware/ from firmware_directories
- **device:** klee: Drop Unmap_Super_Devices() from Check_Pending_Merges

## 2026-08-23

- **device:** klee: Add embedded weaver for Global ROM
- **device:** klee: Fallback to lazy unmount for /odm on EBUSY
- **device:** klee: Add support for ICS haptics

## 2026-08-24

- **device:** klee: Document tree layout and GitHub Actions build flow
- **device:** klee: Group config files by function and add section docs
- **device:** klee: Move first-party sources into src/
- **device:** klee: Consolidate helper scripts into tools/

## 2026-08-25

- **device:** klee: Switch runner to `ubuntu-24.04`
- **device:** klee: Cut load-haptic-modules boot delay from 20s to 1s
- **device:** klee: Drop `com.android.media.swcodec.apex` from loadApexImages
- **device:** klee: klee: Always return to `fox_14.1` instead of `broken repo`

## 2026-08-26

- **device:** klee: Auto-start `touch_report` HAL on boot in recovery
- **device:** klee: Allow choosing runner for build job

## 2026-08-27

- **device:** klee: Retry format data after metadata wipe on merge-status failure
- **device:** klee: Use prebuilt `libklee_libcxx_compat.so` for keymint service
- **device:** Revert "klee: Drop /odm/firmware/ from firmware_directories"
- **device:** klee: Fix vendor_boot cache/flash on custom kernel with baseband_guard

## 2026-09-01

- **device:** klee: Fallback to lazy unmount for /vendor on EBUSY
- **device:** klee: Force periodic re-flip on idle to avoid DSI buffer underrun flicker

## 2026-09-02

- **core:** libfs_avb: Allow LKs patched with fenrir to boot on AOSP _(picked from Mashopy)_
- **recovery:** recovery: Adapt for POCO X8 Pro / REDMI Turbo 5 (klee)
- **device:** klee: Use our fork repo auto sync instead of manual sync

## 2026-09-03

- **device:** klee: Correct remkte
- **device:** Revert "klee: Auto-start `touch_report` HAL on boot in recovery"
- **device:** klee: Switch pixel format to `RGB_565`

## 2026-09-04

- **recovery:** minuitwrp: Fix RGB_565 blank screen by syncing DRM format with base_format
- **recovery:** minuitwrp: Fix screenshot heap overflow on non-32bpp surfaces
- **recovery:** libpixelflinger: Swap R/B channel bit positions for RGB_565
- **recovery:** minuitwrp: Sync gr_color() R/B swap with RGB_565 format table
- **recovery:** minuitwrp: bypass GGL blit for RGB565 screenshot capture

## 2026-09-05

- **recovery:** recovery: Fixup [1/2]
- **recovery:** partitionmanager: skip free-space refresh during active sideload/update_engine install _(picked from claude)_
