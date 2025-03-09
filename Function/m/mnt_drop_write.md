# Function: <code>mnt_drop_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581120576,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:476",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "fs/open.c:vfs_truncate",
        "fs/open.c:chmod_common",
        "fs/open.c:SyS_chown",
        "fs/open.c:SyS_lchown",
        "fs/namei.c:done_path_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:utimes_common",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120576,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581286381,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:476",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:utimes_common",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286320,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581365037,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:475",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:utimes_common",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364976,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581420429,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:476",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:utimes_common",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420368,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581570237,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:530",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file_path"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:utimes_common",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561984,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718128,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:530",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718128,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804896,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:447",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804896,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924144,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924144,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996544,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996544,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230240,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_tmpfile",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:utimes_common",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230240,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280208,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_tmpfile",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:vfs_utimes",
        "fs/init.c:init_chown",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280208,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582305376,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:450",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:vfs_utimes",
        "fs/init.c:init_chown",
        "fs/quota/quota.c:__ia32_sys_quotactl_path",
        "fs/quota/quota.c:__x64_sys_quotactl_path",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305376,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624720,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:452",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:vfs_utimes",
        "fs/init.c:init_chown",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624720,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583163680,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:468",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:vfs_utimes",
        "fs/init.c:init_chown",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_setxattr",
        "io_uring/io_uring.c:io_fsetxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583163680,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739056,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:583",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:vfs_utimes",
        "fs/init.c:init_chown",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_fsetxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739056,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583955632,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:478",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:vfs_utimes",
        "fs/init.c:init_chown",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_fsetxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955632,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164432,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:485",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:vfs_utimes",
        "fs/init.c:init_chown",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_fsetxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164432,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493517288,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__arm64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493517288,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227069376,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:utimes_common",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227069376,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287082496,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287082496,
      "name": "mnt_drop_write",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273184026,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273184026,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965280,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965280,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902848,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902848,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956560,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956560,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void mnt_drop_write(struct vfsmount * mnt)
```

```json
{
  "name": "mnt_drop_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026976,
      "name": "mnt_drop_write",
      "external": true,
      "loc": "fs/namespace.c:444",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_setxattr",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026976,
      "name": "mnt_drop_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
