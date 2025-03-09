# Function: <code>vfs_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581041536,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2650",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "ipc/mqueue.c:do_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041536,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581204400,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2871",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "ipc/mqueue.c:do_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581204400,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581284544,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2835",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "ipc/mqueue.c:do_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284544,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581334224,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2880",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334224,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581475232,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2878",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475232,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581635728,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2879",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635728,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581723744,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2898",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723744,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581841520,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2896",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841520,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581913984,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913984,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582141888,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2791",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141888,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582188928,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2789",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188928,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int vfs_create(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215696,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2898",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215696,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int vfs_create(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582533648,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2967",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_mknodat",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582533648,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int vfs_create(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583047696,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:3063",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_create",
        "fs/namei.c:do_mknodat",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047696,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int vfs_create(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583613376,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:3101",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_create",
        "fs/namei.c:do_mknodat",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613376,
      "name": "vfs_create",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_create(struct mnt_idmap * idmap, struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583837104,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:3178",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_create",
        "fs/namei.c:do_mknodat",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837104,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int vfs_create(struct mnt_idmap * idmap, struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584043120,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:3186",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_create",
        "fs/namei.c:do_mknodat",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584043120,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493394344,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493394344,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226976156,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226976156,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286943888,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286943888,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273108302,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273108302,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581882720,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882720,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581820320,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820320,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874032,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874032,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int vfs_create(struct inode * dir, struct dentry * dentry, umode_t mode, bool want_excl)
```

```json
{
  "name": "vfs_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581939776,
      "name": "vfs_create",
      "external": true,
      "loc": "fs/namei.c:2889",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939776,
      "name": "vfs_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
<code>dir, dentry, mode, want_excl</code> ➡️ <code>mnt_userns, dir, dentry, mode, want_excl</code>
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
