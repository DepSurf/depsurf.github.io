# Function: <code>set_nlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581104016,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:305",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:make_empty_dir_inode",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104016,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269792,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:312",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269792,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581347776,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:314",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347776,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403232,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:315",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403232,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544864,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:315",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544864,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699600,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699600,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581785936,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785936,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581904272,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:330",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904272,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976768,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976768,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582208352,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:335",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/kernfs/inode.c:kernfs_refresh_inode",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208352,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582255824,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:336",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/kernfs/inode.c:kernfs_refresh_inode",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255824,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582281552,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:336",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/kernfs/inode.c:kernfs_refresh_inode",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281552,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582599600,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:340",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/kernfs/inode.c:kernfs_refresh_inode",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599600,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583132560,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:364",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/kernfs/inode.c:kernfs_refresh_inode",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132560,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583703072,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:362",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/kernfs/inode.c:kernfs_refresh_inode",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703072,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583920560,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:362",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/kernfs/inode.c:kernfs_refresh_inode",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920560,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126256,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:363",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/kernfs/inode.c:kernfs_refresh_inode",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126256,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493484856,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493484856,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227047580,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227047580,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287044416,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287044416,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273160304,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273160304,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581945504,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945504,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883072,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883072,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936816,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936816,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void set_nlink(struct inode * inode, unsigned int nlink)
```

```json
{
  "name": "set_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008256,
      "name": "set_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:make_empty_dir_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/stack.c:fsstack_copy_attr_all",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/generic.c:proc_getattr",
        "fs/ext4/inline.c:ext4_try_create_inline_dir",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008256,
      "name": "set_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
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
