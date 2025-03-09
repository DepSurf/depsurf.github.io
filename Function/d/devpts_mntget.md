# Function: <code>devpts_mntget</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581869008,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:159",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869008,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018992,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:173",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018992,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207296,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:173",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207296,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302352,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:171",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302352,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468704,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468704,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567648,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567648,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875872,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875872,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948736,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948736,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582976192,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582976192,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311792,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311792,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819040,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819040,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584441200,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584441200,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669984,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:150",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669984,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584902736,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:149",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902736,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494213296,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494213296,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227644768,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227644768,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287908784,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287908784,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273671538,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273671538,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582536384,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536384,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582473552,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473552,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582526864,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526864,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```

```json
{
  "name": "devpts_mntget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582607536,
      "name": "devpts_mntget",
      "external": true,
      "loc": "fs/devpts/inode.c:168",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607536,
      "name": "devpts_mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct vfsmount * devpts_mntget(struct file * filp, struct pts_fs_info * fsi)
```
</details>
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
