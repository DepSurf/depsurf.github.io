# Struct: <code>nfs_fattr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec64 atime;
    struct timespec64 mtime;
    struct timespec64 ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec64 pre_mtime;
    struct timespec64 pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
    struct nfs4_label * label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec64 atime;
    struct timespec64 mtime;
    struct timespec64 ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec64 pre_mtime;
    struct timespec64 pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
    struct nfs4_label * label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec64 atime;
    struct timespec64 mtime;
    struct timespec64 ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec64 pre_mtime;
    struct timespec64 pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
    struct nfs4_label * label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec64 atime;
    struct timespec64 mtime;
    struct timespec64 ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec64 pre_mtime;
    struct timespec64 pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
    struct nfs4_label * label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec64 atime;
    struct timespec64 mtime;
    struct timespec64 ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec64 pre_mtime;
    struct timespec64 pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
    struct nfs4_label * label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec64 atime;
    struct timespec64 mtime;
    struct timespec64 ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec64 pre_mtime;
    struct timespec64 pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
    struct nfs4_label * label;
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
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
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
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec atime;
    struct timespec mtime;
    struct timespec ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec pre_mtime;
    struct timespec pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct nfs_fattr {
    unsigned int valid;
    umode_t mode;
    __u32 nlink;
    kuid_t uid;
    kgid_t gid;
    dev_t rdev;
    __u64 size;
    union (anon) du;
    struct nfs_fsid fsid;
    __u64 fileid;
    __u64 mounted_on_fileid;
    struct timespec64 atime;
    struct timespec64 mtime;
    struct timespec64 ctime;
    __u64 change_attr;
    __u64 pre_change_attr;
    __u64 pre_size;
    struct timespec64 pre_mtime;
    struct timespec64 pre_ctime;
    long unsigned int time_start;
    long unsigned int gencount;
    struct nfs4_string * owner_name;
    struct nfs4_string * group_name;
    struct nfs4_threshold * mdsthreshold;
    struct nfs4_label * label;
}
```
</details>
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
