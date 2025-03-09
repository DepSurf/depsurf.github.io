# Function: <code>vfs_mknod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581044128,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3499",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044128,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581203920,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3665",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203920,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581284064,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3622",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284064,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581333744,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3687",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581333744,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581474640,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3685",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:SyS_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474640,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581636608,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3707",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636608,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581723152,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3697",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723152,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581840960,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3696",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840960,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581913424,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913424,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142944,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3520",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142944,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582189920,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3522",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/init.c:init_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:handle_create",
        "net/unix/af_unix.c:unix_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189920,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int vfs_mknod(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582216624,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3670",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/init.c:init_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216624,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
int vfs_mknod(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534640,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3739",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534640,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
int vfs_mknod(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047984,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3833",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047984,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int vfs_mknod(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613712,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3890",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613712,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int vfs_mknod(struct mnt_idmap * idmap, struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583838304,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3970",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583838304,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 762
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
int vfs_mknod(struct mnt_idmap * idmap, struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584044336,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3979",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/init.c:init_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "drivers/base/devtmpfs.c:devtmpfs_work_loop",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584044336,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493395552,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493395552,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226977488,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226977488,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286945584,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286945584,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273109174,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273109174,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581882160,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882160,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581819760,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819760,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581873472,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873472,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int vfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev)
```

```json
{
  "name": "vfs_mknod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581939216,
      "name": "vfs_mknod",
      "external": true,
      "loc": "fs/namei.c:3691",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939216,
      "name": "vfs_mknod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
<code>dir, dentry, mode, dev</code> ➡️ <code>mnt_userns, dir, dentry, mode, dev</code>
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
