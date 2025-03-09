# Function: <code>ihold</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581104176,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_unlinkat",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:blkdev_get",
        "fs/devpts/inode.c:devpts_add_ref",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:SyS_mq_unlink",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104176,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269952,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:396",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:blkdev_get",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:SyS_mq_unlink",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269952,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581347936,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:398",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:blkdev_get",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:SyS_mq_unlink",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347936,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403360,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:396",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:SyS_mq_unlink",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403360,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544992,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:396",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:SyS_mq_unlink",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544992,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699728,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:402",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:blkdev_get",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699728,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581786064,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:402",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:blkdev_get",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786064,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581912921,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:415",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912921,
      "name": "ihold.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581904384,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976896,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976896,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582208416,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:420",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__do_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208416,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582255888,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:421",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/libfs.c:simple_link",
        "fs/ext4/namei.c:__ext4_link",
        "ipc/mqueue.c:__do_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255888,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582281616,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:421",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/libfs.c:simple_link",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/ext4/namei.c:__ext4_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281616,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597968,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:425",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/libfs.c:simple_link",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/ext4/namei.c:__ext4_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597968,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583129760,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:449",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/libfs.c:simple_link",
        "fs/notify/mark.c:__fsnotify_recalc_mask",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/ext4/namei.c:__ext4_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583129760,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699216,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:448",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/libfs.c:simple_link",
        "fs/notify/mark.c:__fsnotify_recalc_mask",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/ext4/namei.c:__ext4_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699216,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917088,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:448",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/libfs.c:simple_link",
        "fs/notify/mark.c:__fsnotify_recalc_mask",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/ext4/namei.c:__ext4_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917088,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122864,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:449",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/libfs.c:simple_link",
        "fs/notify/mark.c:__fsnotify_recalc_mask",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/ext4/namei.c:__ext4_link",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122864,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493483600,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__arm64_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493483600,
      "name": "ihold",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227047796,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__se_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227047796,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287039232,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__se_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287039232,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273160396,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__se_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273160396,
      "name": "ihold",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581945632,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945632,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883200,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883200,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936944,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936944,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void ihold(struct inode * inode)
```

```json
{
  "name": "ihold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008384,
      "name": "ihold",
      "external": true,
      "loc": "fs/inode.c:419",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_link",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/libfs.c:simple_link",
        "fs/block_dev.c:bd_start_claiming",
        "fs/ext4/namei.c:ext4_link",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008384,
      "name": "ihold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
