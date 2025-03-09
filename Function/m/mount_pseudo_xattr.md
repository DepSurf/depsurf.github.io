# Function: <code>mount_pseudo_xattr</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_pseudo_xattr(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct xattr_handler * * xattr, const struct dentry_operations * dops, long unsigned int magic)
```

```json
{
  "name": "mount_pseudo_xattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398544,
      "name": "mount_pseudo_xattr",
      "external": true,
      "loc": "fs/libfs.c:239",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_mount",
        "fs/pipe.c:pipefs_mount",
        "fs/nsfs.c:nsfs_mount",
        "fs/block_dev.c:bd_mount",
        "fs/anon_inodes.c:anon_inodefs_mount",
        "fs/aio.c:aio_mount",
        "drivers/virtio/virtio_balloon.c:balloon_mount",
        "net/socket.c:sockfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398544,
      "name": "mount_pseudo_xattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_pseudo_xattr(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct xattr_handler * * xattr, const struct dentry_operations * dops, long unsigned int magic)
```

```json
{
  "name": "mount_pseudo_xattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581453808,
      "name": "mount_pseudo_xattr",
      "external": true,
      "loc": "fs/libfs.c:240",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_mount",
        "fs/pipe.c:pipefs_mount",
        "fs/nsfs.c:nsfs_mount",
        "fs/block_dev.c:bd_mount",
        "fs/anon_inodes.c:anon_inodefs_mount",
        "fs/aio.c:aio_mount",
        "drivers/virtio/virtio_balloon.c:balloon_mount",
        "drivers/dax/super.c:dax_mount",
        "net/socket.c:sockfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453808,
      "name": "mount_pseudo_xattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_pseudo_xattr(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct xattr_handler * * xattr, const struct dentry_operations * dops, long unsigned int magic)
```

```json
{
  "name": "mount_pseudo_xattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595792,
      "name": "mount_pseudo_xattr",
      "external": true,
      "loc": "fs/libfs.c:240",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_mount",
        "fs/pipe.c:pipefs_mount",
        "fs/nsfs.c:nsfs_mount",
        "fs/block_dev.c:bd_mount",
        "fs/anon_inodes.c:anon_inodefs_mount",
        "fs/aio.c:aio_mount",
        "drivers/virtio/virtio_balloon.c:balloon_mount",
        "drivers/dax/super.c:dax_mount",
        "net/socket.c:sockfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595792,
      "name": "mount_pseudo_xattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_pseudo_xattr(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct xattr_handler * * xattr, const struct dentry_operations * dops, long unsigned int magic)
```

```json
{
  "name": "mount_pseudo_xattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581754032,
      "name": "mount_pseudo_xattr",
      "external": true,
      "loc": "fs/libfs.c:240",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_mount",
        "fs/pipe.c:pipefs_mount",
        "fs/nsfs.c:nsfs_mount",
        "fs/block_dev.c:bd_mount",
        "fs/anon_inodes.c:anon_inodefs_mount",
        "fs/aio.c:aio_mount",
        "drivers/virtio/virtio_balloon.c:balloon_mount",
        "drivers/dax/super.c:dax_mount",
        "net/socket.c:sockfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754032,
      "name": "mount_pseudo_xattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_pseudo_xattr(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct xattr_handler * * xattr, const struct dentry_operations * dops, long unsigned int magic)
```

```json
{
  "name": "mount_pseudo_xattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840560,
      "name": "mount_pseudo_xattr",
      "external": true,
      "loc": "fs/libfs.c:240",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_mount",
        "fs/pipe.c:pipefs_mount",
        "fs/nsfs.c:nsfs_mount",
        "fs/block_dev.c:bd_mount",
        "fs/anon_inodes.c:anon_inodefs_mount",
        "fs/aio.c:aio_mount",
        "drivers/virtio/virtio_balloon.c:balloon_mount",
        "drivers/dax/super.c:dax_mount",
        "net/socket.c:sockfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840560,
      "name": "mount_pseudo_xattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct dentry * mount_pseudo_xattr(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct xattr_handler * * xattr, const struct dentry_operations * dops, long unsigned int magic)
```
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct dentry * mount_pseudo_xattr(struct file_system_type * fs_type, char * name, const struct super_operations * ops, const struct xattr_handler * * xattr, const struct dentry_operations * dops, long unsigned int magic)
```
</details>
</li>
</ul>
