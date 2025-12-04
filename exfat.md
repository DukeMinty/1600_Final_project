# exFAT

*Information sourced from [How-To Geek](https://www.howtogeek.com/235596/whats-the-difference-between-fat32-exfat-and-ntfs/)*

### What is exFAT?

*exFAT* (Extended File Allocation Table), introduced by Microsoft in 2006, was designed as a modern replacement for FAT32 that is optomized for flash drived. It is widely used for USB drives, SD cards, and external SSDs in situations where large file sizes are required.

Unlike FAT32, exFAT supports **files larger than 4 GB** and works efficiently on both large and small storage devices.

exFat is not as widely compatible as Fat32, however it is still more widely accepted than NTFS, allowing for the file system to be used across a variety of OS'.

---

### Attributes

- [x] **Cross-platform compatibility**  
exFAT is supported by Windows, macOS, Linux, most new game consoles, and many more systems.

- [x] **Supports large files & volumes**  
You can store files well over 4 GB, which is an improvement compared to Fat32.

- [x] **Optimized for flash storage**  
exFAT was built for flash memory devices.

- [ ] **No journaling**  
Like FAT32, exFAT does not include journaling features, which exposes you to risk of data corruption.

- [ ] **Limited security features**  
exFAT does not offer permissions, encryption, or other file-level security features found in NTFS.

---

### When should you use it?

exFAT shines in situations where you need **broad compatibility** and the ability to store **large files**. It is ideal for:

- High-capacity USB drives  
- Cameras and camcorders  
- External SSDs that will used across Windows, macOS, and Linux  
- Devices that need to store large videos, photos, backups, or game files  

If you're working across multiple operating systems or handling large media files, exFAT is often the best choice, especially compared to its brother Fat32. However, for internal drives or situations where security and reliability are top priorities, it is not going to be useful. Your OS' preferred file type such as NTFS, APFS, or ext4 are better options.

[← Back](fat32.md)
[Next →](apfs.md)
