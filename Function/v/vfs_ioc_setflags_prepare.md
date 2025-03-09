# Function: <code>vfs_ioc_setflags_prepare</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581904432,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2202",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904432,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976944,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976944,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208272,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2304",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_ioc_setxflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208272,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582255744,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2305",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_ioc_setxflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255744,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493482808,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493482808,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227047972,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227047972,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287044752,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287044752,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273160556,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273160556,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581945680,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945680,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883248,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883248,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936992,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936992,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
```

```json
{
  "name": "vfs_ioc_setflags_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008432,
      "name": "vfs_ioc_setflags_prepare",
      "external": true,
      "loc": "fs/inode.c:2244",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008432,
      "name": "vfs_ioc_setflags_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
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
int vfs_ioc_setflags_prepare(struct inode * inode, unsigned int oldflags, unsigned int flags)
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
