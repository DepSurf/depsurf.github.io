# Function: <code>vfs_fchmod</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fchmod(struct file * file, umode_t mode)
```

```json
{
  "name": "vfs_fchmod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582102462,
      "name": "vfs_fchmod",
      "external": true,
      "loc": "fs/open.c:596",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102672,
      "name": "vfs_fchmod",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fchmod(struct file * file, umode_t mode)
```

```json
{
  "name": "vfs_fchmod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582127309,
      "name": "vfs_fchmod",
      "external": true,
      "loc": "fs/open.c:598",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127520,
      "name": "vfs_fchmod",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fchmod(struct file * file, umode_t mode)
```

```json
{
  "name": "vfs_fchmod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582443949,
      "name": "vfs_fchmod",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582444160,
      "name": "vfs_fchmod",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fchmod(struct file * file, umode_t mode)
```

```json
{
  "name": "vfs_fchmod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582962128,
      "name": "vfs_fchmod",
      "external": true,
      "loc": "fs/open.c:619",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582962368,
      "name": "vfs_fchmod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int vfs_fchmod(struct file * file, umode_t mode)
```

```json
{
  "name": "vfs_fchmod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583520784,
      "name": "vfs_fchmod",
      "external": true,
      "loc": "fs/open.c:619",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583521056,
      "name": "vfs_fchmod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int vfs_fchmod(struct file * file, umode_t mode)
```

```json
{
  "name": "vfs_fchmod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583736224,
      "name": "vfs_fchmod",
      "external": true,
      "loc": "fs/open.c:656",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736496,
      "name": "vfs_fchmod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int vfs_fchmod(struct file * file, umode_t mode)
```

```json
{
  "name": "vfs_fchmod",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583937152,
      "name": "vfs_fchmod",
      "external": true,
      "loc": "fs/open.c:661",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938384,
      "name": "vfs_fchmod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int vfs_fchmod(struct file * file, umode_t mode)
```
</details>
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
