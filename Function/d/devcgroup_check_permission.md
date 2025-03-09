# Function: <code>devcgroup_check_permission</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581462671,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581683354,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581629077,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847587,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581715253,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934723,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581832770,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072505,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581905234,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152345,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584167024,
      "name": "devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:835",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_mknod",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167024,
      "name": "devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584286144,
      "name": "devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:835",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286144,
      "name": "devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584311232,
      "name": "devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:835",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311232,
      "name": "devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698096,
      "name": "devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:835",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_mknod",
        "block/bdev.c:blkdev_get_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698096,
      "name": "devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585362064,
      "name": "devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:836",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_mknod",
        "block/bdev.c:blkdev_get_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362064,
      "name": "devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586112224,
      "name": "devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:861",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_mknod",
        "block/bdev.c:blkdev_get_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112224,
      "name": "devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586350960,
      "name": "devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:860",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_mknod",
        "block/bdev.c:blkdev_get_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586350960,
      "name": "devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586618016,
      "name": "devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:860",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:vfs_mknod",
        "block/bdev.c:bdev_open_by_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618016,
      "name": "devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493385772,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493704684,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226967320,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 3227232224,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286927952,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287309016,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273101540,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273320538,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581873970,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582121081,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581811570,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058521,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581865282,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111561,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devcgroup_check_permission",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581928226,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582184521,
      "name": "devcgroup_check_permission",
      "external": false,
      "loc": "include/linux/device_cgroup.h:24",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```
</details>
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
