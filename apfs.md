# APFS

*Information sourced from [Apple](https://support.apple.com/guide/security/role-of-apple-file-system-seca6147599e/web)*

### What is APFS? 

*APFS* or *Apple File System* is Apple's own file system type which they made in 2017 to replace HFSPlus, and as such is the default file system for all Apple operating systems across MacBooks, iPhones, Apple TVs, Apple Watches, etc.

It is known mainly for its "strong encryption, cloning for files and directories, snapshots, fast directory sizing, and data reliablity" - per their website.

---

### Attributes

- [x] **Optimized for SSDs**  
APFS is built to take advantage of the low-latency performance of solid-state storage, offering faster read/write operations and improved responsiveness across Apple devices.

- [x] **Strong native encryption**  
APFS includes full support for encryption.

- [x] **Snapshots**  
APFS supports snapshots, which create a read-only point-in-time image of the file system, allowing for very reliable and useful backups of file systems.

- [ ] **Limited cross-platform support**  
APFS is only natively supported on Apple devices.

- [ ] **Not ideal for older hardware**  
HDDs do not benefit from APFS’s SSD optimizations.

- [ ] **Not useful for removable drives**  
Many cameras, TVs, and non-Apple consumer devices cannot read APFS, making it unsuitable for formatting on removeable storage devices.

---

### When should you use it?

You should use APFS when working within the **Apple ecosystem** only, it is completely useless otherwise. Its compatibility with Apple devices is stellar, but in the same way that NTFS is stellar with Windows devices: the companies are simple enforcing it to be so.

APFS allows for a very reliable and safe workspace across Apple devices that can allow users to make the most out of their SSDs and the benefits that APFS specifically provides, however it is useless for a workspace where you need cross-device support. Because it is not supported by most devices and is likely going to be read-only on the ones it is supported on, you should almost never format internal drives or external drives to APFS. If a drive is in APFS, it is certainly because it is the internal drive of your apple device. 

For work purposes where more than just Apple devices are necessary, any external drives should be formatted to exFat, as most devices including Apple products accept read and write permissions with it.

[← Back](ext4.md)
[Next →](exfat.md)
