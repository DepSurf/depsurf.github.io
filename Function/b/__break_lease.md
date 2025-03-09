# Function: <code>__break_lease</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581341616,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1390",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/open.c:chmod_common",
        "fs/open.c:chown_common",
        "fs/open.c:do_dentry_open",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/attr.c:notify_change",
        "fs/utimes.c:utimes_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341616,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1163
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522336,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1418",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:SyS_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/utimes.c:utimes_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522336,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1133
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610256,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1442",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:SyS_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/utimes.c:utimes_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610256,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1305
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581667488,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1442",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:SyS_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/utimes.c:utimes_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667488,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1275
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813632,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1452",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:SyS_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/utimes.c:utimes_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813632,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1290
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988304,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1452",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988304,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1278
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582076032,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1571",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076032,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1285
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582238064,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1577",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238064,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1307
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582337792,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337792,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1331
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582627712,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1606",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_setxattr",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/utimes.c:utimes_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627712,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1650
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582699952,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1607",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_setxattr",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/utimes.c:vfs_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582699952,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1598
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582729136,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1607",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_setxattr",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/utimes.c:vfs_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582729136,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1599
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583056048,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1510",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_setxattr",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/utimes.c:vfs_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056048,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1596
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531328,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1485",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_setxattr",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/utimes.c:vfs_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531328,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1945
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131680,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1471",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_setxattr",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/utimes.c:vfs_utimes",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/posix_acl.c:vfs_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131680,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1943
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584358848,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1472",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_setxattr",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/utimes.c:vfs_utimes",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/posix_acl.c:vfs_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358848,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1943
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584577248,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1486",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:vfs_setxattr",
        "fs/xattr.c:__vfs_setxattr_locked",
        "fs/utimes.c:vfs_utimes",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/posix_acl.c:vfs_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584577248,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1943
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493919208,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493919208,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1696
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227404500,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change",
        "fs/utimes.c:utimes_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227404500,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1636
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287570656,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287570656,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1952
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273474030,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273474030,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1448
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582306528,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306528,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1331
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244288,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244288,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1331
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297008,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297008,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1331
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
int __break_lease(struct inode * inode, unsigned int mode, unsigned int type)
```

```json
{
  "name": "__break_lease",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381232,
      "name": "__break_lease",
      "external": true,
      "loc": "fs/locks.c:1603",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:vfs_truncate",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:vfs_unlink",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381232,
      "name": "__break_lease",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1505
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
