# Function: <code>current_fs_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct timespec current_fs_time(struct super_block * sb)
```

```json
{
  "name": "current_fs_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807872,
      "name": "current_fs_time",
      "external": true,
      "loc": "kernel/time/time.c:240",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:atime_needs_update",
        "fs/inode.c:touch_atime",
        "fs/attr.c:notify_change",
        "fs/bad_inode.c:make_bad_inode",
        "fs/locks.c:lease_get_mtime",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807872,
      "name": "current_fs_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct timespec current_fs_time(struct super_block * sb)
```

```json
{
  "name": "current_fs_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835728,
      "name": "current_fs_time",
      "external": true,
      "loc": "kernel/time/time.c:240",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/bad_inode.c:make_bad_inode",
        "fs/locks.c:lease_get_mtime",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/debugfs/inode.c:debugfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835728,
      "name": "current_fs_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct timespec current_fs_time(struct super_block * sb)
```

```json
{
  "name": "current_fs_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864784,
      "name": "current_fs_time",
      "external": true,
      "loc": "kernel/time/time.c:240",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864784,
      "name": "current_fs_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct timespec current_fs_time(struct super_block * sb)
```
</details>
</li>
</ul>
