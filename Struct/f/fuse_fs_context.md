# Struct: <code>fuse_fs_context</code>

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
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool legacy_opts_show;
    bool dax;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    struct dax_device * dax_dev;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool legacy_opts_show;
    bool dax;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    struct dax_device * dax_dev;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    struct file * file;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool legacy_opts_show;
    bool dax;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    struct dax_device * dax_dev;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    struct file * file;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool legacy_opts_show;
    enum fuse_dax_mode dax_mode;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    struct dax_device * dax_dev;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    struct file * file;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool legacy_opts_show;
    enum fuse_dax_mode dax_mode;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    struct dax_device * dax_dev;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    struct file * file;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool legacy_opts_show;
    enum fuse_dax_mode dax_mode;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    struct dax_device * dax_dev;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    struct file * file;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool legacy_opts_show;
    enum fuse_dax_mode dax_mode;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    struct dax_device * dax_dev;
    void * * fudptr;
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
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
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
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
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
struct fuse_fs_context {
    int fd;
    unsigned int rootmode;
    kuid_t user_id;
    kgid_t group_id;
    bool is_bdev;
    bool fd_present;
    bool rootmode_present;
    bool user_id_present;
    bool group_id_present;
    bool default_permissions;
    bool allow_other;
    bool destroy;
    bool no_control;
    bool no_force_umount;
    bool no_mount_options;
    unsigned int max_read;
    unsigned int blksize;
    const char * subtype;
    void * * fudptr;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool legacy_opts_show</code>
</li>
<li>
<b>Field added. </b>
<code>bool dax</code>
</li>
<li>
<b>Field added. </b>
<code>struct dax_device * dax_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>bool no_mount_options</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct file * file</code>
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
<code>enum fuse_dax_mode dax_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>bool dax</code>
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
