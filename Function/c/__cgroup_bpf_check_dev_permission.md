# Function: <code>__cgroup_bpf_check_dev_permission</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623488,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:526",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623488,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751888,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:624",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751888,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816336,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:681",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816336,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907152,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:754",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907152,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960304,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960304,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581131872,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1101",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_check_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131872,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166000,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1125",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_check_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166000,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182992,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1129",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_check_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182992,
      "name": "__cgroup_bpf_check_dev_permission",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581423600,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1159",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_check_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581423600,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749840,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1306",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_check_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749840,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164864,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1520",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_check_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164864,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361792,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1520",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_check_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361792,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528688,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1535",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_check_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528688,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492309728,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492309728,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226191524,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226191524,
      "name": "__cgroup_bpf_check_dev_permission",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285548496,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285548496,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272435720,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272435720,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929104,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929104,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875168,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875168,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920352,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920352,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_check_dev_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981344,
      "name": "__cgroup_bpf_check_dev_permission",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:764",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:inode_permission",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981344,
      "name": "__cgroup_bpf_check_dev_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
