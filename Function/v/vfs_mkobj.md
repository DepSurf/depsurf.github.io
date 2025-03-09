# Function: <code>vfs_mkobj</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634928,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2900",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634928,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581724560,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2919",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724560,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842320,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2917",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842320,
      "name": "vfs_mkobj",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581914784,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914784,
      "name": "vfs_mkobj",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140928,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2812",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140928,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188016,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2810",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188016,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582214832,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2919",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214832,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532752,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2988",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532752,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583051248,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:3084",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583051248,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583617504,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:3122",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617504,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583836080,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:3201",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583836080,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584042096,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:3209",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042096,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493395152,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493395152,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226977052,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226977052,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286945008,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286945008,
      "name": "vfs_mkobj",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273108882,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273108882,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883520,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883520,
      "name": "vfs_mkobj",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821120,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821120,
      "name": "vfs_mkobj",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874832,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874832,
      "name": "vfs_mkobj",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```

```json
{
  "name": "vfs_mkobj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940576,
      "name": "vfs_mkobj",
      "external": true,
      "loc": "fs/namei.c:2910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940576,
      "name": "vfs_mkobj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int vfs_mkobj(struct dentry * dentry, umode_t mode, int (*)(struct dentry *, umode_t, void *) f, void * arg)
```
</details>
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
