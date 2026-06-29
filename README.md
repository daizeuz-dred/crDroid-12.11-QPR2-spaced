<img width="2760" height="1720" alt="crdroid_spaced_banner_v6" src="https://github.com/user-attachments/assets/824196ec-4a9b-4828-af99-b018c1efe3b5" />


# crDroid 12.11 QPR2  
### Realme 8i / Narzo 50 (`spaced`)
### Android 16  
### Maintained by **DΞΞZNUTZ**

---

### 📋 What's Changed

### 📱 Device
* Brought up device tree for crDroid v12.11 QPR2
* Fixed NDK platform library loading on vendor partition
* Tuned block I/O queue depth for better storage performance
* Enabled 120Hz as default framework refresh rate
* Improved SurfaceFlinger and display pipeline tuning
* Imported phase offsets from Motorola for smoother rendering
* Enabled Dolby AudioFX support
* Fixed powerhint frequency values to match actual OPP table
* Added signed release keys
* Various init and props cleanup

### 🔧 Kernel
* Switched ZRAM default compression to ZSTD for better memory efficiency
* Removed SDCARD_FS in favor of FUSE
* Fixed zsmalloc rwlock build issue on some configs
* Downgraded a noisy GPU clock warning to debug-only
* Cleaned up WLAN firmware fallback handling
* Added KernelSU support
* Updated build script for Apex target

### ⚠️ Notes
* Clean flash recommended
* Dirty flash from previous crDroid builds may work but is not guaranteed

---

### 📝 **Notes & Installation**
* A clean flash is highly recommended if migrating from another ROM.
* If your facing minimal screen flickering, you can fix it by yourself by flashing this [**module**](https://t.me/DEEZProjects/23).

### 🤝 **Credits & Thanks**
* Huge thanks to `@HELLINFIX` for the foundational source collaboration and device tree support.
* Thanks to `@ViaanLarryROMS` for the assistance in adding Sony Dolby.
* Thanks to @hxfuxyy for teaching me how to implement OTA updates.

---

### 🤝🏻 **Buy me a coffee?**
* Github Sponsor: [**Sponsor**](https://github.com/sponsors/daizeuz-dred)
* Sociabuzz: [**Sponsor**](https://sociabuzz.com/daizeuzdred/tribe)

---
