# Struct: <code>vfio_device_ops</code>

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
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
    int (*)(void *, char *) match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
    int (*)(void *, char *) match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(struct vfio_device *) open;
    void (*)(struct vfio_device *) release;
    ssize_t (*)(struct vfio_device *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct vfio_device *, const char *, size_t, loff_t *) write;
    long int (*)(struct vfio_device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct vfio_device *, struct vm_area_struct *) mmap;
    void (*)(struct vfio_device *, unsigned int) request;
    int (*)(struct vfio_device *, char *) match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(struct vfio_device *) open_device;
    void (*)(struct vfio_device *) close_device;
    ssize_t (*)(struct vfio_device *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct vfio_device *, const char *, size_t, loff_t *) write;
    long int (*)(struct vfio_device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct vfio_device *, struct vm_area_struct *) mmap;
    void (*)(struct vfio_device *, unsigned int) request;
    int (*)(struct vfio_device *, char *) match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(struct vfio_device *) open_device;
    void (*)(struct vfio_device *) close_device;
    ssize_t (*)(struct vfio_device *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct vfio_device *, const char *, size_t, loff_t *) write;
    long int (*)(struct vfio_device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct vfio_device *, struct vm_area_struct *) mmap;
    void (*)(struct vfio_device *, unsigned int) request;
    int (*)(struct vfio_device *, char *) match;
    int (*)(struct vfio_device *, u32, void *, size_t) device_feature;
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
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
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
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
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
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
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
<code>int (*)(void *, char *) match</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(void *) open</code> ➡️ <code>int (*)(struct vfio_device *) open</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(void *) release</code> ➡️ <code>void (*)(struct vfio_device *) release</code>
</li>
<li>
<b>Field type changed. </b>
<code>ssize_t (*)(void *, char *, size_t, loff_t *) read</code> ➡️ <code>ssize_t (*)(struct vfio_device *, char *, size_t, loff_t *) read</code>
</li>
<li>
<b>Field type changed. </b>
<code>ssize_t (*)(void *, const char *, size_t, loff_t *) write</code> ➡️ <code>ssize_t (*)(struct vfio_device *, const char *, size_t, loff_t *) write</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int (*)(void *, unsigned int, long unsigned int) ioctl</code> ➡️ <code>long int (*)(struct vfio_device *, unsigned int, long unsigned int) ioctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(void *, struct vm_area_struct *) mmap</code> ➡️ <code>int (*)(struct vfio_device *, struct vm_area_struct *) mmap</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(void *, unsigned int) request</code> ➡️ <code>void (*)(struct vfio_device *, unsigned int) request</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(void *, char *) match</code> ➡️ <code>int (*)(struct vfio_device *, char *) match</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct vfio_device *) open_device</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct vfio_device *) close_device</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct vfio_device *) open</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct vfio_device *) release</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct vfio_device *, u32, void *, size_t) device_feature</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(struct vfio_device *) open_device;
    void (*)(struct vfio_device *) close_device;
    ssize_t (*)(struct vfio_device *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct vfio_device *, const char *, size_t, loff_t *) write;
    long int (*)(struct vfio_device *, unsigned int, long unsigned int) ioctl;
    int (*)(struct vfio_device *, struct vm_area_struct *) mmap;
    void (*)(struct vfio_device *, unsigned int) request;
    int (*)(struct vfio_device *, char *) match;
    int (*)(struct vfio_device *, u32, void *, size_t) device_feature;
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
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
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
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
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
struct vfio_device_ops {
    char * name;
    int (*)(void *) open;
    void (*)(void *) release;
    ssize_t (*)(void *, char *, size_t, loff_t *) read;
    ssize_t (*)(void *, const char *, size_t, loff_t *) write;
    long int (*)(void *, unsigned int, long unsigned int) ioctl;
    int (*)(void *, struct vm_area_struct *) mmap;
    void (*)(void *, unsigned int) request;
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
