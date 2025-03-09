# Function: <code>notify_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111744,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:232",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_truncate",
        "fs/open.c:chmod_common",
        "fs/open.c:chown_common",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:utimes_common",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111744,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277232,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:208",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:utimes_common",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277232,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1074
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581355568,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:221",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:utimes_common",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355568,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410912,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:222",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:utimes_common",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410912,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552512,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:utimes_common",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552512,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1074
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581708656,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:225",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708656,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1111
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795168,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:226",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795168,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581913968,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:226",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913968,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1146
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986256,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986256,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219984,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:utimes_common",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219984,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1223
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267440,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:vfs_utimes",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/base/devtmpfs.c:handle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267440,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1268
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
int notify_change(struct user_namespace * mnt_userns, struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582292880,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:282",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:vfs_utimes",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582292880,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1336
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
int notify_change(struct user_namespace * mnt_userns, struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611792,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:310",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:vfs_utimes",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611792,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int notify_change(struct user_namespace * mnt_userns, struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583144400,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:326",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:vfs_utimes",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583144400,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
int notify_change(struct user_namespace * mnt_userns, struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583717872,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:380",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:__file_remove_privs",
        "fs/utimes.c:vfs_utimes",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583717872,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1458
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
int notify_change(struct mnt_idmap * idmap, struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583935136,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:381",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:__file_remove_privs",
        "fs/utimes.c:vfs_utimes",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583935136,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1197
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
int notify_change(struct mnt_idmap * idmap, struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584141376,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:381",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:__file_remove_privs",
        "fs/utimes.c:vfs_utimes",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141376,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1226
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493499088,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493499088,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227056968,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/utimes.c:utimes_common",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227056968,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287061200,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287061200,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1560
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273172120,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273172120,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954992,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954992,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892560,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892560,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946304,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946304,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int notify_change(struct dentry * dentry, struct iattr * attr, struct inode * * delegated_inode)
```

```json
{
  "name": "notify_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582016336,
      "name": "notify_change",
      "external": true,
      "loc": "fs/attr.c:223",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:do_truncate",
        "fs/inode.c:file_remove_privs",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_truncate",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582016336,
      "name": "notify_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, attr, delegated_inode</code> ➡️ <code>mnt_userns, dentry, attr, delegated_inode</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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
