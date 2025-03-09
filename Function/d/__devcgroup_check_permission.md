# Function: <code>__devcgroup_check_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602784,
      "name": "__devcgroup_check_permission",
      "external": false,
      "loc": "security/device_cgroup.c:813",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:__devcgroup_inode_permission",
        "security/device_cgroup.c:devcgroup_inode_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602784,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847856,
      "name": "__devcgroup_check_permission",
      "external": false,
      "loc": "security/device_cgroup.c:813",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_inode_mknod",
        "security/device_cgroup.c:__devcgroup_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847856,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943904,
      "name": "__devcgroup_check_permission",
      "external": false,
      "loc": "security/device_cgroup.c:813",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_inode_mknod",
        "security/device_cgroup.c:__devcgroup_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943904,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582993984,
      "name": "__devcgroup_check_permission",
      "external": false,
      "loc": "security/device_cgroup.c:813",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_inode_mknod",
        "security/device_cgroup.c:__devcgroup_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582993984,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158352,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:805",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158352,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363856,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:805",
      "file": "security/device_cgroup.c",
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
      "addr": 18446744071583363856,
      "name": "__devcgroup_check_permission",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482608,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:805",
      "file": "security/device_cgroup.c",
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
      "addr": 18446744071583482608,
      "name": "__devcgroup_check_permission",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668688,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 18446744071583668688,
      "name": "__devcgroup_check_permission",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583775696,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 18446744071583775696,
      "name": "__devcgroup_check_permission",
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495577584,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 18446603336495577584,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228939588,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 3228939588,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289674400,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 13835058055289674400,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274744456,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 18446743936274744456,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744432,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 18446744071583744432,
      "name": "__devcgroup_check_permission",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681488,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 18446744071583681488,
      "name": "__devcgroup_check_permission",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728208,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 18446744071583728208,
      "name": "__devcgroup_check_permission",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```

```json
{
  "name": "__devcgroup_check_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583829024,
      "name": "__devcgroup_check_permission",
      "external": true,
      "loc": "security/device_cgroup.c:804",
      "file": "security/device_cgroup.c",
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
      "addr": 18446744071583829024,
      "name": "__devcgroup_check_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access)
```
</details>
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
