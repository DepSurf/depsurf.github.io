# Function: <code>vfs_fchown</code>

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
int vfs_fchown(struct file * file, uid_t user, gid_t group)
```

```json
{
  "name": "vfs_fchown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582103948,
      "name": "vfs_fchown",
      "external": true,
      "loc": "fs/open.c:734",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchown"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582103776,
      "name": "vfs_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fchown(struct file * file, uid_t user, gid_t group)
```

```json
{
  "name": "vfs_fchown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582128860,
      "name": "vfs_fchown",
      "external": true,
      "loc": "fs/open.c:742",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchown"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582128688,
      "name": "vfs_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fchown(struct file * file, uid_t user, gid_t group)
```

```json
{
  "name": "vfs_fchown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582445500,
      "name": "vfs_fchown",
      "external": true,
      "loc": "fs/open.c:739",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchown"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445328,
      "name": "vfs_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fchown(struct file * file, uid_t user, gid_t group)
```

```json
{
  "name": "vfs_fchown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582964020,
      "name": "vfs_fchown",
      "external": true,
      "loc": "fs/open.c:764",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchown"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963808,
      "name": "vfs_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int vfs_fchown(struct file * file, uid_t user, gid_t group)
```

```json
{
  "name": "vfs_fchown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583522900,
      "name": "vfs_fchown",
      "external": true,
      "loc": "fs/open.c:796",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchown"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522672,
      "name": "vfs_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int vfs_fchown(struct file * file, uid_t user, gid_t group)
```

```json
{
  "name": "vfs_fchown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583738228,
      "name": "vfs_fchown",
      "external": true,
      "loc": "fs/open.c:828",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchown"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738000,
      "name": "vfs_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int vfs_fchown(struct file * file, uid_t user, gid_t group)
```

```json
{
  "name": "vfs_fchown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583940116,
      "name": "vfs_fchown",
      "external": true,
      "loc": "fs/open.c:848",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchown"
      ],
      "caller_func": [
        "init/initramfs.c:do_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939888,
      "name": "vfs_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int vfs_fchown(struct file * file, uid_t user, gid_t group)
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
