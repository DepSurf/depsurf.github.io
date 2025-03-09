# Function: <code>user_path_at_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581058048,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2329",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_truncate",
        "fs/open.c:SyS_access",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_chown",
        "fs/open.c:SyS_lchown",
        "fs/stat.c:vfs_fstatat",
        "fs/stat.c:SyS_readlink",
        "fs/namei.c:SyS_link",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:SyS_name_to_handle_at",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058048,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218944,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2553",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown",
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_access",
        "fs/open.c:do_sys_truncate",
        "fs/stat.c:SyS_readlink",
        "fs/stat.c:vfs_fstatat",
        "fs/namei.c:SyS_link",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:SyS_name_to_handle_at",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218944,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296640,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2542",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown",
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_access",
        "fs/open.c:do_sys_truncate",
        "fs/stat.c:SyS_readlink",
        "fs/stat.c:vfs_fstatat",
        "fs/namei.c:SyS_link",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:SyS_name_to_handle_at",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296640,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346208,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2587",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown",
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_access",
        "fs/stat.c:SyS_readlink",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:SyS_link",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:SyS_name_to_handle_at",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346208,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487600,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2585",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_lchown",
        "fs/open.c:SyS_chown",
        "fs/open.c:SyS_chmod",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_access",
        "fs/stat.c:SyS_readlink",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:SyS_link",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:SyS_name_to_handle_at",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487600,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647648,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2581",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647648,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581733920,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2605",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733920,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853312,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2603",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853312,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925776,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925776,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582160167,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2643",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_linkat"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_do_get",
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:ksys_umount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156016,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582201767,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2641",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_linkat"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_do_get",
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201520,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582226536,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2731",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_linkat"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:__ia32_sys_quotactl_path",
        "fs/quota/quota.c:__x64_sys_quotactl_path",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226288,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543376,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2797",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543376,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583071088,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2893",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_sys_truncate",
        "fs/stat.c:do_readlinkat",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583071088,
      "name": "user_path_at_empty",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583637520,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2872",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_sys_truncate",
        "fs/stat.c:do_readlinkat",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583637520,
      "name": "user_path_at_empty",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854672,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2903",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_sys_truncate",
        "fs/stat.c:do_readlinkat",
        "fs/namespace.c:__ia32_sys_mount_setattr",
        "fs/namespace.c:__x64_sys_mount_setattr",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_move_mount",
        "fs/namespace.c:__do_sys_move_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854672,
      "name": "user_path_at_empty",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061856,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2920",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "fs/open.c:do_fchownat",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:__x64_sys_truncate",
        "fs/stat.c:do_readlinkat",
        "fs/namespace.c:__ia32_sys_mount_setattr",
        "fs/namespace.c:__x64_sys_mount_setattr",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_move_mount",
        "fs/namespace.c:__do_sys_move_mount",
        "fs/namespace.c:__ia32_sys_mount",
        "fs/namespace.c:__x64_sys_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:__ia32_sys_oldumount",
        "fs/namespace.c:__x64_sys_oldumount",
        "fs/namespace.c:__ia32_sys_umount",
        "fs/namespace.c:__x64_sys_umount",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061856,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493406368,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:__arm64_sys_move_mount",
        "fs/namespace.c:__arm64_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__arm64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__arm64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493406368,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226992192,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_move_mount",
        "fs/namespace.c:__se_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/fhandle.c:__se_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226992192,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286964816,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_move_mount",
        "fs/namespace.c:__se_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__se_sys_name_to_handle_at",
        "fs/fhandle.c:__se_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286964816,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273117608,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_move_mount",
        "fs/namespace.c:__se_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/fhandle.c:__se_sys_name_to_handle_at",
        "fs/fhandle.c:__se_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273117608,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894512,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894512,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832112,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832112,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885824,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885824,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int user_path_at_empty(int dfd, const char * name, unsigned int flags, struct path * path, int * empty)
```

```json
{
  "name": "user_path_at_empty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955328,
      "name": "user_path_at_empty",
      "external": true,
      "loc": "fs/namei.c:2596",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_fchownat",
        "fs/open.c:do_fchmodat",
        "fs/open.c:ksys_chroot",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/stat.c:do_readlinkat",
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__ia32_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:__x64_sys_move_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:path_listxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:path_setxattr",
        "fs/utimes.c:do_utimes",
        "fs/statfs.c:user_statfs",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/fhandle.c:__ia32_sys_name_to_handle_at",
        "fs/fhandle.c:__x64_sys_name_to_handle_at",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955328,
      "name": "user_path_at_empty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
