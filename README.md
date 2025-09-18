# RaspberryPi-Linux-Drivers
“Experiments with Linux kernel driver development on Raspberry Pi. Includes character drivers, GPIO, I2C, SPI, and device tree overlays. Goal: transition from embedded firmware to Linux kernel programming.”

# RaspberryPi-Linux-Drivers

This repository documents my learning path in **Linux kernel driver development** using Raspberry Pi.  
It bridges the gap between **embedded firmware (STM32 + FreeRTOS)** and **Linux kernel space programming**.

---

## 🛠️ Phases

### **Phase 1 – Linux Kernel Basics**
- Compile and load a simple "Hello World" kernel module.
- Explore `insmod`, `rmmod`, `lsmod`, and `dmesg`.
- Understand kernel vs user space.

### **Phase 2 – Character Drivers**
- Write a simple character driver.
- Implement open, read, write, release functions.
- Use `mknod` to create device files in `/dev`.

### **Phase 3 – GPIO Drivers**
- Control Raspberry Pi GPIO using kernel drivers.
- Handle interrupts from a push button.
- Implement debouncing in kernel space.

### **Phase 4 – I2C and SPI Drivers**
- Write drivers to communicate with I2C/SPI sensors.
- Parse device tree overlays for hardware configuration.
- Compare Linux driver model vs STM32 bare-metal drivers.

### **Phase 5 – Advanced Topics**
- Work with kernel synchronization (semaphores, spinlocks).
- Explore kernel debugging with `printk` and `gdb`.
- Understand memory management and DMA basics.

---

## 🎯 Goal
To gain **hands-on experience in Linux kernel programming**, focusing on **device drivers** for Raspberry Pi hardware.

## 🛠️ Tools & Platforms
- Raspberry Pi 4 / Raspberry Pi Zero
- Raspbian / Raspberry Pi OS
- GCC / Makefile for kernel modules
- Git for version control

---

