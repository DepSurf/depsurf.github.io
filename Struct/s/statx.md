# Struct: <code>statx</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64 stx_mnt_id;
    __u64 __spare2;
    __u64[12] __spare3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64 stx_mnt_id;
    __u64 __spare2;
    __u64[12] __spare3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64 stx_mnt_id;
    __u64 __spare2;
    __u64[12] __spare3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64 stx_mnt_id;
    __u64 __spare2;
    __u64[12] __spare3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64 stx_mnt_id;
    __u64 __spare2;
    __u64[12] __spare3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64 stx_mnt_id;
    __u32 stx_dio_mem_align;
    __u32 stx_dio_offset_align;
    __u64[12] __spare3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64 stx_mnt_id;
    __u32 stx_dio_mem_align;
    __u32 stx_dio_offset_align;
    __u64[12] __spare3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64 stx_mnt_id;
    __u32 stx_dio_mem_align;
    __u32 stx_dio_offset_align;
    __u64[12] __spare3;
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
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
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
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct statx {
    __u32 stx_mask;
    __u32 stx_blksize;
    __u64 stx_attributes;
    __u32 stx_nlink;
    __u32 stx_uid;
    __u32 stx_gid;
    __u16 stx_mode;
    __u16[1] __spare0;
    __u64 stx_ino;
    __u64 stx_size;
    __u64 stx_blocks;
    __u64 stx_attributes_mask;
    struct statx_timestamp stx_atime;
    struct statx_timestamp stx_btime;
    struct statx_timestamp stx_ctime;
    struct statx_timestamp stx_mtime;
    __u32 stx_rdev_major;
    __u32 stx_rdev_minor;
    __u32 stx_dev_major;
    __u32 stx_dev_minor;
    __u64[14] __spare2;
}
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u64 stx_mnt_id</code>
</li>
<li>
<b>Field added. </b>
<code>__u64[12] __spare3</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64[14] __spare2</code> ➡️ <code>__u64 __spare2</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 stx_dio_mem_align</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 stx_dio_offset_align</code>
</li>
<li>
<b>Field removed. </b>
<code>__u64 __spare2</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
