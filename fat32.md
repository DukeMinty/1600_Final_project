# FAT32

*Information sourced from [How-To Geek](https://www.howtogeek.com/235596/whats-the-difference-between-fat32-exfat-and-ntfs/)*

### What is FAT32?

*FAT* (File Allocation Table) and its later version *FAT32* are some of the oldest and most widely supported file systems ever developed. Originally created by Microsoft in the late 1970s and updated throughout the 1990s, FAT32 became the standard for USB drives, memory cards, and devices that needed maximum cross-platform compatibility due to its age.

FAT32 is known mainly for its simplicity, universal support, and lightweight structure. Unlike modern file systems, it does not support advanced security or journaling features, but its broad compatibility makes it ideal for portable storage devices and consumer electronics.

---

### Attributes

- [x] **Universal compatibility**  
FAT/FAT32 is readable and writable by virtually every major operating system and device.

- [x] **Lightweight and simple**  
The file system is easy for devices to implement, which is why it remains popular for removable media.

- [x] **Low overhead**  
Because FAT32 lacks complex metadata and journaling, it uses very little system overhead and works efficiently on small drives.

- [ ] **File size limitations**  
FAT32 cannot store individual files larger than **4 GB**, making it unsuitable for modern large files.

- [ ] **Lack of reliability features**  
Unlike NTFS, FAT32 does **not** support journaling. This makes it more vulnerable to corruption.

- [ ] **No permissions or encryption**  
FAT32 offers no file-level security. Anyone with access to the drive can view or modify its contents, and no built-in encryption exists.

---

### When should you use it?

You should almost never use FAT32. Its main use-case is for older machines that require FAT32 to function properly.

The 4 GB file size limit and lack of security features makes FAT32 nigh incompatible with modern workspaces. For transferring files between devices, a more modern and sidely-accepted file system like exFAT is a better option.

[← Back](ntfs.md)
[Next →](exfat.md)
