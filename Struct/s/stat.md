# Struct: <code>stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct stat {
    long unsigned int st_dev;
    long unsigned int st_ino;
    unsigned int st_mode;
    unsigned int st_nlink;
    unsigned int st_uid;
    unsigned int st_gid;
    long unsigned int st_rdev;
    long unsigned int __pad1;
    long int st_size;
    int st_blksize;
    int __pad2;
    long int st_blocks;
    long int st_atime;
    long unsigned int st_atime_nsec;
    long int st_mtime;
    long unsigned int st_mtime_nsec;
    long int st_ctime;
    long unsigned int st_ctime_nsec;
    unsigned int __unused4;
    unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct stat {
    long unsigned int st_dev;
    long unsigned int st_ino;
    short unsigned int st_mode;
    short unsigned int st_nlink;
    short unsigned int st_uid;
    short unsigned int st_gid;
    long unsigned int st_rdev;
    long unsigned int st_size;
    long unsigned int st_blksize;
    long unsigned int st_blocks;
    long unsigned int st_atime;
    long unsigned int st_atime_nsec;
    long unsigned int st_mtime;
    long unsigned int st_mtime_nsec;
    long unsigned int st_ctime;
    long unsigned int st_ctime_nsec;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct stat {
    long unsigned int st_dev;
    ino_t st_ino;
    long unsigned int st_nlink;
    mode_t st_mode;
    uid_t st_uid;
    gid_t st_gid;
    long unsigned int st_rdev;
    off_t st_size;
    long unsigned int st_blksize;
    long unsigned int st_blocks;
    long unsigned int st_atime;
    long unsigned int st_atime_nsec;
    long unsigned int st_mtime;
    long unsigned int st_mtime_nsec;
    long unsigned int st_ctime;
    long unsigned int st_ctime_nsec;
    long unsigned int __unused4;
    long unsigned int __unused5;
    long unsigned int __unused6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct stat {
    long unsigned int st_dev;
    long unsigned int st_ino;
    unsigned int st_mode;
    unsigned int st_nlink;
    unsigned int st_uid;
    unsigned int st_gid;
    long unsigned int st_rdev;
    long unsigned int __pad1;
    long int st_size;
    int st_blksize;
    int __pad2;
    long int st_blocks;
    long int st_atime;
    long unsigned int st_atime_nsec;
    long int st_mtime;
    long unsigned int st_mtime_nsec;
    long int st_ctime;
    long unsigned int st_ctime_nsec;
    unsigned int __unused4;
    unsigned int __unused5;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct stat {
    __kernel_ulong_t st_dev;
    __kernel_ulong_t st_ino;
    __kernel_ulong_t st_nlink;
    unsigned int st_mode;
    unsigned int st_uid;
    unsigned int st_gid;
    unsigned int __pad0;
    __kernel_ulong_t st_rdev;
    __kernel_long_t st_size;
    __kernel_long_t st_blksize;
    __kernel_long_t st_blocks;
    __kernel_ulong_t st_atime;
    __kernel_ulong_t st_atime_nsec;
    __kernel_ulong_t st_mtime;
    __kernel_ulong_t st_mtime_nsec;
    __kernel_ulong_t st_ctime;
    __kernel_ulong_t st_ctime_nsec;
    __kernel_long_t[3] __unused;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int __pad1</code>
</li>
<li>
<b>Field added. </b>
<code>int __pad2</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int __unused4</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int __unused5</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int __pad0</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_long_t[3] __unused</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_dev</code> ➡️ <code>long unsigned int st_dev</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ino</code> ➡️ <code>long unsigned int st_ino</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_nlink</code> ➡️ <code>unsigned int st_nlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_rdev</code> ➡️ <code>long unsigned int st_rdev</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_size</code> ➡️ <code>long int st_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_blksize</code> ➡️ <code>int st_blksize</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_blocks</code> ➡️ <code>long int st_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_atime</code> ➡️ <code>long int st_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_atime_nsec</code> ➡️ <code>long unsigned int st_atime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_mtime</code> ➡️ <code>long int st_mtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_mtime_nsec</code> ➡️ <code>long unsigned int st_mtime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ctime</code> ➡️ <code>long int st_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ctime_nsec</code> ➡️ <code>long unsigned int st_ctime_nsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int __unused4</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int __unused5</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int __pad0</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_long_t[3] __unused</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_dev</code> ➡️ <code>long unsigned int st_dev</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ino</code> ➡️ <code>long unsigned int st_ino</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_nlink</code> ➡️ <code>short unsigned int st_nlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int st_mode</code> ➡️ <code>short unsigned int st_mode</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int st_uid</code> ➡️ <code>short unsigned int st_uid</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int st_gid</code> ➡️ <code>short unsigned int st_gid</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_rdev</code> ➡️ <code>long unsigned int st_rdev</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_size</code> ➡️ <code>long unsigned int st_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_blksize</code> ➡️ <code>long unsigned int st_blksize</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_blocks</code> ➡️ <code>long unsigned int st_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_atime</code> ➡️ <code>long unsigned int st_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_atime_nsec</code> ➡️ <code>long unsigned int st_atime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_mtime</code> ➡️ <code>long unsigned int st_mtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_mtime_nsec</code> ➡️ <code>long unsigned int st_mtime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ctime</code> ➡️ <code>long unsigned int st_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ctime_nsec</code> ➡️ <code>long unsigned int st_ctime_nsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int __unused4</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int __unused5</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int __unused6</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int __pad0</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_long_t[3] __unused</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_dev</code> ➡️ <code>long unsigned int st_dev</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ino</code> ➡️ <code>ino_t st_ino</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_nlink</code> ➡️ <code>long unsigned int st_nlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int st_mode</code> ➡️ <code>mode_t st_mode</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int st_uid</code> ➡️ <code>uid_t st_uid</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int st_gid</code> ➡️ <code>gid_t st_gid</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_rdev</code> ➡️ <code>long unsigned int st_rdev</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_size</code> ➡️ <code>off_t st_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_blksize</code> ➡️ <code>long unsigned int st_blksize</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_blocks</code> ➡️ <code>long unsigned int st_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_atime</code> ➡️ <code>long unsigned int st_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_atime_nsec</code> ➡️ <code>long unsigned int st_atime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_mtime</code> ➡️ <code>long unsigned int st_mtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_mtime_nsec</code> ➡️ <code>long unsigned int st_mtime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ctime</code> ➡️ <code>long unsigned int st_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ctime_nsec</code> ➡️ <code>long unsigned int st_ctime_nsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int __pad1</code>
</li>
<li>
<b>Field added. </b>
<code>int __pad2</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int __unused4</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int __unused5</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int __pad0</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_long_t[3] __unused</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_dev</code> ➡️ <code>long unsigned int st_dev</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ino</code> ➡️ <code>long unsigned int st_ino</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_nlink</code> ➡️ <code>unsigned int st_nlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_rdev</code> ➡️ <code>long unsigned int st_rdev</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_size</code> ➡️ <code>long int st_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_blksize</code> ➡️ <code>int st_blksize</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_long_t st_blocks</code> ➡️ <code>long int st_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_atime</code> ➡️ <code>long int st_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_atime_nsec</code> ➡️ <code>long unsigned int st_atime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_mtime</code> ➡️ <code>long int st_mtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_mtime_nsec</code> ➡️ <code>long unsigned int st_mtime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ctime</code> ➡️ <code>long int st_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t st_ctime_nsec</code> ➡️ <code>long unsigned int st_ctime_nsec</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
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
