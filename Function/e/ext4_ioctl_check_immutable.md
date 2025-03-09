# Function: <code>ext4_ioctl_check_immutable</code>

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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582633200,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633200,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582734192,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734192,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583041616,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583041616,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583117664,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:279",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117664,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583151663,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:283",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_fileattr_set"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583492431,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:282",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_fileattr_set"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584019216,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:511",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_fileattr_set"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584650592,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:522",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_fileattr_set"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584873856,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:520",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_fileattr_set"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585106720,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:530",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_fileattr_set"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494392120,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494392120,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227828968,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227828968,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288133536,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288133536,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273815732,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273815732,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582702928,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702928,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582640096,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640096,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582692784,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692784,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
```

```json
{
  "name": "ext4_ioctl_check_immutable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582777168,
      "name": "ext4_ioctl_check_immutable",
      "external": false,
      "loc": "fs/ext4/ioctl.c:277",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777168,
      "name": "ext4_ioctl_check_immutable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
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
int ext4_ioctl_check_immutable(struct inode * inode, __u32 new_projid, unsigned int flags)
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
