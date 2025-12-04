# FAT32

*Information sourced from [How-ToGeek](https://www.howtogeek.com/235596/whats-the-difference-between-fat32-exfat-and-ntfs/)

### What is FAT32?

*FAT* (File Allocation Table) and its later version *FAT32* are some of the oldest and most widely supported file systems ever developed. Originally created by Microsoft in the late 1970s and updated throughout the 1990s, FAT32 became the standard for USB drives, memory cards, and devices that needed maximum cross-platform compatibility.

FAT32 is known mainly for its simplicity, universal support, and lightweight structure. Unlike modern file systems, it does not support advanced security or journaling features, but its broad compatibility makes it ideal for portable storage devices and consumer electronics.

One important limitation is its **maximum file size of 4 GB** and **maximum volume size of 8 TB** (with certain formatting tools).

---

### Attributes

- [x] **Universal compatibility**  
FAT/FAT32 is readable and writable by virtually every major operating system and device, including Windows, macOS, Linux, game consoles, cameras, and embedded systems.

- [x] **Lightweight and simple**  
The file system is easy for devices to implement, which is why it remains popular for removable media.

- [x] **Low overhead**  
Because FAT/FAT32 lacks complex metadata and journaling, it uses very little system overhead and works efficiently on small drives.

- [ ] **File size limitations**  
FAT32 cannot store individual files larger than **4 GB**, making it unsuitable for modern large videos, disk images, or other big data files.

- [ ] **Lack of reliability features**  
Unlike NTFS, FAT32 does **not** support journaling. This makes it more vulnerable to corruption if a device loses power or is removed improperly.

- [ ] **No permissions or encryption**  
FAT/FAT32 offers no file-level security. Anyone with access to the drive can view or modify its contents, and no built-in encryption exists.

---

### When should you use it?

You should use FAT32 when **maximum compatibility** is your primary goal. Devices like cameras, gaming consoles, embedded systems, and older machines often require FAT/FAT32 to function properly.

FAT32 is also great for:  
- USB drives that need to work everywhere  
- Memory cards for cameras and handheld devices  
- Small-capacity drives where NTFS or other systems add unnecessary overhead  

However, if you need to store files larger than 4 GB or require security features, FAT32 will not be suitable. In those cases, a more modern file system like exFAT or NTFS is a better option.

If your setup involves transferring data across many different platforms, FAT/FAT32 remains one of the simplest and most universally accepted choices available.
