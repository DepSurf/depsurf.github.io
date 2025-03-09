# Function: <code>vfs_ioc_fssetxattr_check</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903264,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2226",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903264,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975504,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975504,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207568,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2328",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207568,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582255040,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2329",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255040,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493481240,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493481240,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227046192,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227046192,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287042352,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287042352,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273158956,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273158956,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944240,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944240,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881808,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881808,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935552,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935552,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```

```json
{
  "name": "vfs_ioc_fssetxattr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582006992,
      "name": "vfs_ioc_fssetxattr_check",
      "external": true,
      "loc": "fs/inode.c:2268",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582006992,
      "name": "vfs_ioc_fssetxattr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
```
</details>
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
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int vfs_ioc_fssetxattr_check(struct inode * inode, const struct fsxattr * old_fa, struct fsxattr * fa)
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
