# Struct: <code>kernfs_iattrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    struct iattr ia_iattr;
    void * ia_secdata;
    u32 ia_secdata_len;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    struct iattr ia_iattr;
    void * ia_secdata;
    u32 ia_secdata_len;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    struct iattr ia_iattr;
    void * ia_secdata;
    u32 ia_secdata_len;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    struct iattr ia_iattr;
    void * ia_secdata;
    u32 ia_secdata_len;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    struct iattr ia_iattr;
    void * ia_secdata;
    u32 ia_secdata_len;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    struct iattr ia_iattr;
    void * ia_secdata;
    u32 ia_secdata_len;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    struct iattr ia_iattr;
    void * ia_secdata;
    u32 ia_secdata_len;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
    atomic_t nr_user_xattrs;
    atomic_t user_xattr_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
    atomic_t nr_user_xattrs;
    atomic_t user_xattr_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
    atomic_t nr_user_xattrs;
    atomic_t user_xattr_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
    atomic_t nr_user_xattrs;
    atomic_t user_xattr_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
    atomic_t nr_user_xattrs;
    atomic_t user_xattr_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
    atomic_t nr_user_xattrs;
    atomic_t user_xattr_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
    atomic_t nr_user_xattrs;
    atomic_t user_xattr_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
    atomic_t nr_user_xattrs;
    atomic_t user_xattr_size;
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
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
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
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kernfs_iattrs {
    kuid_t ia_uid;
    kgid_t ia_gid;
    struct timespec64 ia_atime;
    struct timespec64 ia_mtime;
    struct timespec64 ia_ctime;
    struct simple_xattrs xattrs;
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>kuid_t ia_uid</code>
</li>
<li>
<b>Field added. </b>
<code>kgid_t ia_gid</code>
</li>
<li>
<b>Field added. </b>
<code>struct timespec64 ia_atime</code>
</li>
<li>
<b>Field added. </b>
<code>struct timespec64 ia_mtime</code>
</li>
<li>
<b>Field added. </b>
<code>struct timespec64 ia_ctime</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iattr ia_iattr</code>
</li>
<li>
<b>Field removed. </b>
<code>void * ia_secdata</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 ia_secdata_len</code>
</li>
</ul>
</details>
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
<code>atomic_t nr_user_xattrs</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t user_xattr_size</code>
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
