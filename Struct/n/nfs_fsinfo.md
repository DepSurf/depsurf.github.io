# Struct: <code>nfs_fsinfo</code>

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
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
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
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    __u32 xattr_support;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    __u32 xattr_support;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    __u32 xattr_support;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    __u32 xattr_support;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    __u32 xattr_support;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    __u32 xattr_support;
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
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
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
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
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
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 nlayouttypes</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 layouttype</code> ➡️ <code>__u32[8] layouttype</code>
</li>
</ul>
</details>
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
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct nfs_fsinfo {
    struct nfs_fattr * fattr;
    __u32 rtmax;
    __u32 rtpref;
    __u32 rtmult;
    __u32 wtmax;
    __u32 wtpref;
    __u32 wtmult;
    __u32 dtpref;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    __u32 lease_time;
    __u32 nlayouttypes;
    __u32[8] layouttype;
    __u32 blksize;
    __u32 clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    __u32 xattr_support;
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
