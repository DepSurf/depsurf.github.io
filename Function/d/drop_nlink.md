# Function: <code>drop_nlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581104096,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:271",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unlink",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_unlink",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_link",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104096,
      "name": "drop_nlink",
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269872,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:278",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269872,
      "name": "drop_nlink",
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581347856,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:280",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347856,
      "name": "drop_nlink",
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403296,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:281",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403296,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544928,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:281",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544928,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699664,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:283",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699664,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581786000,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:283",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786000,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581904368,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:296",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912899,
      "name": "drop_nlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581904336,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976832,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976832,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582208800,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:301",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_recursive_removal",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208800,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582256272,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:302",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_recursive_removal",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256272,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582281856,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:302",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_recursive_removal",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281856,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582599904,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:306",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_recursive_removal",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599904,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583133104,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:330",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_recursive_removal",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133104,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583703472,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:328",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_recursive_removal",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703472,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583921008,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:328",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_recursive_removal",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921008,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126704,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:329",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_recursive_removal",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_entry_unlinked",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126704,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493483808,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493483808,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227047680,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_update_dir_count",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227047680,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287044528,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287044528,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273157298,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273157298,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581945568,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945568,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883136,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883136,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936880,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936880,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void drop_nlink(struct inode * inode)
```

```json
{
  "name": "drop_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008320,
      "name": "drop_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_rmdir",
        "mm/shmem.c:shmem_unlink",
        "fs/dcache.c:d_tmpfile",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_rmdir",
        "fs/libfs.c:simple_unlink",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/efivarfs/inode.c:efivarfs_unlink",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "ipc/mqueue.c:mqueue_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008320,
      "name": "drop_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
