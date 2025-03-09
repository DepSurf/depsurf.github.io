# Struct: <code>compat_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    u32 st_dev;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    u32 st_rdev;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    u32 st_dev;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    u32 st_rdev;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    u32 st_dev;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    u32 st_rdev;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct compat_stat {
    u32 st_dev;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    u32 st_rdev;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
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
struct compat_stat {
    compat_dev_t st_dev;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_ushort_t st_nlink;
    __compat_uid16_t st_uid;
    __compat_gid16_t st_gid;
    compat_dev_t st_rdev;
    compat_off_t st_size;
    compat_off_t st_blksize;
    compat_off_t st_blocks;
    old_time32_t st_atime;
    compat_ulong_t st_atime_nsec;
    old_time32_t st_mtime;
    compat_ulong_t st_mtime_nsec;
    old_time32_t st_ctime;
    compat_ulong_t st_ctime_nsec;
    compat_ulong_t[2] __unused4;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid32_t st_uid;
    __compat_gid32_t st_gid;
    compat_dev_t st_rdev;
    compat_off_t st_size;
    compat_off_t st_blksize;
    compat_off_t st_blocks;
    old_time32_t st_atime;
    u32 st_atime_nsec;
    old_time32_t st_mtime;
    u32 st_mtime_nsec;
    old_time32_t st_ctime;
    u32 st_ctime_nsec;
    u32[2] __unused4;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u16 __pad1</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 __pad2</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_dev_t st_dev</code> ➡️ <code>u32 st_dev</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_dev_t st_rdev</code> ➡️ <code>u32 st_rdev</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>u16 __pad1</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 __pad2</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 __unused5</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_nlink_t st_nlink</code> ➡️ <code>compat_ushort_t st_nlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>__compat_uid_t st_uid</code> ➡️ <code>__compat_uid16_t st_uid</code>
</li>
<li>
<b>Field type changed. </b>
<code>__compat_gid_t st_gid</code> ➡️ <code>__compat_gid16_t st_gid</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_size</code> ➡️ <code>compat_off_t st_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_blksize</code> ➡️ <code>compat_off_t st_blksize</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_blocks</code> ➡️ <code>compat_off_t st_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_atime</code> ➡️ <code>old_time32_t st_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_atime_nsec</code> ➡️ <code>compat_ulong_t st_atime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_mtime</code> ➡️ <code>old_time32_t st_mtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_mtime_nsec</code> ➡️ <code>compat_ulong_t st_mtime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_ctime</code> ➡️ <code>old_time32_t st_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_ctime_nsec</code> ➡️ <code>compat_ulong_t st_ctime_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 __unused4</code> ➡️ <code>compat_ulong_t[2] __unused4</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u16 __pad1</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 __pad2</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 __unused5</code>
</li>
<li>
<b>Field type changed. </b>
<code>__compat_uid_t st_uid</code> ➡️ <code>__compat_uid32_t st_uid</code>
</li>
<li>
<b>Field type changed. </b>
<code>__compat_gid_t st_gid</code> ➡️ <code>__compat_gid32_t st_gid</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_size</code> ➡️ <code>compat_off_t st_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_blksize</code> ➡️ <code>compat_off_t st_blksize</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_blocks</code> ➡️ <code>compat_off_t st_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_atime</code> ➡️ <code>old_time32_t st_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_mtime</code> ➡️ <code>old_time32_t st_mtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 st_ctime</code> ➡️ <code>old_time32_t st_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 __unused4</code> ➡️ <code>u32[2] __unused4</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct compat_stat {
    compat_dev_t st_dev;
    u16 __pad1;
    compat_ino_t st_ino;
    compat_mode_t st_mode;
    compat_nlink_t st_nlink;
    __compat_uid_t st_uid;
    __compat_gid_t st_gid;
    compat_dev_t st_rdev;
    u16 __pad2;
    u32 st_size;
    u32 st_blksize;
    u32 st_blocks;
    u32 st_atime;
    u32 st_atime_nsec;
    u32 st_mtime;
    u32 st_mtime_nsec;
    u32 st_ctime;
    u32 st_ctime_nsec;
    u32 __unused4;
    u32 __unused5;
}
```
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
