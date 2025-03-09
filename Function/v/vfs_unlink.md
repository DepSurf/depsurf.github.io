# Function: <code>vfs_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046192,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3793",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "ipc/mqueue.c:SyS_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046192,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205616,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3936",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:SyS_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205616,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581285760,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3893",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:SyS_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285760,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328848,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3958",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:SyS_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328848,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473952,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3956",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:SyS_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473952,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633984,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3990",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633984,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581719808,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3979",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719808,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837216,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3979",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837216,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909680,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909680,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144768,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3805",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144768,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582185792,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3806",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582185792,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
int vfs_unlink(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209696,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:4004",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209696,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
int vfs_unlink(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582539392,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:4078",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539392,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int vfs_unlink(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583054080,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:4173",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583054080,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int vfs_unlink(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620432,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:4229",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620432,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int vfs_unlink(struct mnt_idmap * idmap, struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835056,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:4306",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835056,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int vfs_unlink(struct mnt_idmap * idmap, struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584041072,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:4315",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041072,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493390440,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__arm64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493390440,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226971760,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226971760,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286939088,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286939088,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273105312,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273105312,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878416,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878416,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581816016,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816016,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581869728,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869728,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int vfs_unlink(struct inode * dir, struct dentry * dentry, struct inode * * delegated_inode)
```

```json
{
  "name": "vfs_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934128,
      "name": "vfs_unlink",
      "external": true,
      "loc": "fs/namei.c:3974",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_unlinkat",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934128,
      "name": "vfs_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
<code>dir, dentry, delegated_inode</code> ➡️ <code>mnt_userns, dir, dentry, delegated_inode</code>
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
