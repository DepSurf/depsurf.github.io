# Function: <code>__fsnotify_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __fsnotify_parent(struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268048,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:89",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_open",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:d_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/fat/file.c:fat_generic_ioctl",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268048,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int __fsnotify_parent(struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433760,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:89",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:d_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_generic_ioctl",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433760,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514880,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:89",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:d_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_generic_ioctl",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514880,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567664,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:d_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_generic_ioctl",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567664,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581711936,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:d_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_generic_ioctl",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711936,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878864,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:d_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_generic_ioctl",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878864,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581963456,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:155",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:d_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_generic_ioctl",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963456,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582096144,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:142",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582096144,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173504,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173504,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582464544,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:180",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464544,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int __fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582491632,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:180",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491632,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int __fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806128,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:180",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806128,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int __fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583359952,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:178",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_fallocate",
        "io_uring/io_uring.c:__io_complete_rw_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359952,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
int __fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583943392,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:178",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "io_uring/sync.c:io_fallocate",
        "io_uring/openclose.c:io_openat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943392,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
int __fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584166704,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:178",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "io_uring/sync.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166704,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
int __fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584380864,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:178",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_write",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:vfs_iter_read",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/read_write.c:rw_verify_area",
        "fs/file_table.c:__fput",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "io_uring/sync.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584380864,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493728464,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__arm64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493728464,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227253948,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227253948,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287336032,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287336032,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273338386,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/fat/file.c:fat_generic_ioctl",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273338386,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142240,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142240,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582079680,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079680,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132720,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132720,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```

```json
{
  "name": "__fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205760,
      "name": "__fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205760,
      "name": "__fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
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
int __fsnotify_parent(const struct path * path, struct dentry * dentry, __u32 mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```
</details>
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
