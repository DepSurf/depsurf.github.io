# Function: <code>inode_set_ctime_current</code>

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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 inode_set_ctime_current(struct inode * inode)
```

```json
{
  "name": "inode_set_ctime_current",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584128533,
      "name": "inode_set_ctime_current",
      "external": true,
      "loc": "fs/inode.c:2508",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_update_timestamps"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_xattr_handler_set",
        "mm/shmem.c:shmem_xattr_handler_set",
        "mm/shmem.c:shmem_fileattr_set",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_unlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:alloc_anon_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_timestamp",
        "fs/libfs.c:simple_rename_timestamp",
        "fs/libfs.c:simple_rename_timestamp",
        "fs/libfs.c:simple_rename_timestamp",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/libfs.c:simple_recursive_removal",
        "fs/libfs.c:simple_recursive_removal",
        "fs/posix_acl.c:simple_set_acl",
        "fs/configfs/inode.c:configfs_create",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_tmpfile",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:mqueue_read_file",
        "security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents",
        "security/apparmor/policy_unpack.c:__aa_loaddata_update",
        "security/apparmor/policy_unpack.c:__aa_loaddata_update",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129328,
      "name": "inode_set_ctime_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct timespec64 inode_set_ctime_current(struct inode * inode)
```
</details>
</li>
</ul>
