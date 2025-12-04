# NTFS

*Information sourced from [Microsoft](https://learn.microsoft.com/en-us/windows-server/storage/file-server/ntfs-overview) and [TechTarget](https://www.techtarget.com/searchwindowsserver/definition/NTFS)*

### What is NTFS? 

*NTFS* or *New Technology File System* is Microsoft's own file system type, and as such is the default file system for modern Windows-based operating systems. Due to this, it is probably the most common file system out there. If you use a Windows PC, your boot drive is formatted in NTFS- Microsoft will not allow it to be installed in any other format.

It is known mainly for its reliability, security, and ability to support large volumes of data: **up to 8 petabytes**!

You personally will never need to hold that much data, but for Microsoft and their data centers, it is an important feature of the file system. 

---

### Attributes

- [x] **Large file & volume support**
      
NTFS supports larger volumes than any other system.


- [x] **Reliability**

NTFS keeps a journal of file-system changes to automatically restore data loss.


- [x] **Security**

NTFS's built-in security features let administrators grant permissions to sensitive data, restricting access to certain users.

- [x] **Performance**

NTFS uses file compression which provides better storage per-file than some other systems and increases transfer speeds.

- [ ] **Limited OS compatibility**

NTFS is read-only with non-Windows OS', such as macOS or Linux.

- [ ] **Lack of small-volume support**

NTFS has a lot of space overhead, which leads to drives needing to be at least 400mb to be compatible with the system.

- [ ] **No file encryption**

While NTFS provides data encryption, it doesn't support file encryption. This can allow anyone to view the data stored on an NTFS volume by using disk editing utility.

---

### When should you use it?

If you are running Windows, you don't have a choice. NTFS is the only option for your boot drive. You will at least have to use it for that purpose.

For excess drives, I would argue that it's also best to just format them to also be NTFS. Unless you have a more specific use-case that we will discuss later, NTFS covers most of the bases anyone needs. In a Windows-centric setup, it will provide the best support for everything you need to do. 

Aside from that, if you are someone who has multiple OS' and needs to transfer read-only files to your non-Windows ones, you should also consider NTFS. In my experience it is the fastest format for transferring data and the best for transferring large files to.


[← Back](introduction.md)
[Next →](fat_fat32.md)
