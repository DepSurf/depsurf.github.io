# Struct: <code>proc_ops</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct kiocb *, struct iov_iter *) proc_read_iter;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct kiocb *, struct iov_iter *) proc_read_iter;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct kiocb *, struct iov_iter *) proc_read_iter;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct kiocb *, struct iov_iter *) proc_read_iter;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct kiocb *, struct iov_iter *) proc_read_iter;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct kiocb *, struct iov_iter *) proc_read_iter;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct kiocb *, struct iov_iter *) proc_read_iter;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct proc_ops {
    unsigned int proc_flags;
    int (*)(struct inode *, struct file *) proc_open;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) proc_read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) proc_write;
    loff_t (*)(struct file *, loff_t, int) proc_lseek;
    int (*)(struct inode *, struct file *) proc_release;
    __poll_t (*)(struct file *, struct poll_table_struct *) proc_poll;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) proc_compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) proc_mmap;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) proc_get_unmapped_area;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>ssize_t (*)(struct kiocb *, struct iov_iter *) proc_read_iter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
