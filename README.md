# DarkniusX Kernel Source (android12-5.10)

<p align="center">
  <img src="https://img.shields.io/badge/Kernel-Linux%205.10.272-blue?style=for-the-badge&logo=linux" alt="Linux Version">
  <img src="https://img.shields.io/badge/GKI-Android%2012%20(KMI%209)-green?style=for-the-badge&logo=android" alt="GKI KMI 9">
  <img src="https://img.shields.io/badge/SUSFS-v1.5.x-purple?style=for-the-badge" alt="SUSFS">
  <img src="https://img.shields.io/badge/NTSYNC-Enabled-brightgreen?style=for-the-badge" alt="NTSYNC">
  <img src="https://img.shields.io/badge/License-GPL--2.0-red?style=for-the-badge" alt="License">
</p>

Official Linux Kernel source tree for **DarkniusX**, a universal Generic Kernel Image (GKI) for Android 12+ devices running kernel version `5.10` (KMI generation 9).

---

## 🚀 Integrated Enhancements

* **Linux Base:** 5.10.272 (Android Common Kernel `common-android12-5.10`).
* **SUSFS v1.5.x:** VFS hooks and superuser root hiding infrastructure built directly into the kernel core (`fs/susfs.c`, `include/linux/susfs*.h`).
* **NTSYNC Driver:** High-performance NT synchronization primitives emulation driver (`/dev/ntsync` via `drivers/misc/ntsync.c`) for low-overhead Windows gaming emulation in Android (Mobox, Winlator, Box64, Wine).
* **Performance Defconfig:** Includes optimizations for PREEMPT, BBR TCP congestion control, and I/O schedulers.

---

## 🔗 Main Project & Downloads

For build scripts, pre-built AnyKernel3 flashable zip releases, and documentation, visit the main hub:

👉 **[DarkniusX Release Hub & Toolkit](https://github.com/Raffxzr/DarkniusX)**

---

## 📄 License

* This repository is licensed under the **GNU General Public License v2.0 (GPL-2.0)**.
