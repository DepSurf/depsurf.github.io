# Struct: <code>vfio_iommu_driver_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, struct iommu_group *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
    int (*)(void *, dma_addr_t, void *, size_t, bool) dma_rw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, struct iommu_group *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
    int (*)(void *, dma_addr_t, void *, size_t, bool) dma_rw;
    struct iommu_domain * (*)(void *, struct iommu_group *) group_iommu_domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, struct iommu_group *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
    int (*)(void *, dma_addr_t, void *, size_t, bool) dma_rw;
    struct iommu_domain * (*)(void *, struct iommu_group *) group_iommu_domain;
    void (*)(void *, enum vfio_iommu_notify_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, struct iommu_group *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
    int (*)(void *, dma_addr_t, void *, size_t, bool) dma_rw;
    struct iommu_domain * (*)(void *, struct iommu_group *) group_iommu_domain;
    void (*)(void *, enum vfio_iommu_notify_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct iommu_group *, enum vfio_group_type) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, struct iommu_group *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
    int (*)(void *, dma_addr_t, void *, size_t, bool) dma_rw;
    struct iommu_domain * (*)(void *, struct iommu_group *) group_iommu_domain;
    void (*)(void *, enum vfio_iommu_notify_type) notify;
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(void *, dma_addr_t, void *, size_t, bool) dma_rw</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages</code> ➡️ <code>int (*)(void *, struct iommu_group *, long unsigned int *, int, int, long unsigned int *) pin_pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct iommu_domain * (*)(void *, struct iommu_group *) group_iommu_domain</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(void *, enum vfio_iommu_notify_type) notify</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>ssize_t (*)(void *, char *, size_t, loff_t *) read</code>
</li>
<li>
<b>Field removed. </b>
<code>ssize_t (*)(void *, const char *, size_t, loff_t *) write</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(void *, struct vm_area_struct *) mmap</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(void *, struct iommu_group *) attach_group</code> ➡️ <code>int (*)(void *, struct iommu_group *, enum vfio_group_type) attach_group</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct iommu_group *, enum vfio_group_type) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, struct iommu_group *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
    int (*)(void *, dma_addr_t, void *, size_t, bool) dma_rw;
    struct iommu_domain * (*)(void *, struct iommu_group *) group_iommu_domain;
    void (*)(void *, enum vfio_iommu_notify_type) notify;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct vfio_iommu_driver_ops {
    char * name;
    struct module * owner;
    void * (*)(long unsigned int) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    int (*)(void *, struct iommu_group *) attach_group;
    void (*)(void *, struct iommu_group *) detach_group;
    int (*)(void *, long unsigned int *, int, int, long unsigned int *) pin_pages;
    int (*)(void *, long unsigned int *, int) unpin_pages;
    int (*)(void *, long unsigned int *, struct notifier_block *) register_notifier;
    int (*)(void *, struct notifier_block *) unregister_notifier;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
