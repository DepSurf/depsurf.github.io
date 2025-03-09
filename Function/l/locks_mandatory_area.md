# Function: <code>locks_mandatory_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int locks_mandatory_area(int read_write, struct inode * inode, struct file * filp, loff_t offset, size_t count)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338736,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1241",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:rw_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338736,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520224,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1269",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520224,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609440,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1293",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609440,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671376,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1293",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671376,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581817648,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1303",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817648,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581992416,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1303",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992416,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582081392,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1423",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081392,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582243152,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1419",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582243152,
      "name": "locks_mandatory_area",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342928,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342928,
      "name": "locks_mandatory_area",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582633184,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633184,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705328,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1445",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:rw_verify_area",
        "fs/remap_range.c:remap_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705328,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
  "name": "locks_mandatory_area",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "locks_mandatory_area",
      "external": false,
      "loc": "include/linux/fs.h:2628",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "locks_mandatory_area",
      "external": false,
      "loc": "include/linux/fs.h:2628",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493927016,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493927016,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227399256,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227399256,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287563856,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287563856,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273478730,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273478730,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311664,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311664,
      "name": "locks_mandatory_area",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249424,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249424,
      "name": "locks_mandatory_area",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302144,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302144,
      "name": "locks_mandatory_area",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
```

```json
{
  "name": "locks_mandatory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375456,
      "name": "locks_mandatory_area",
      "external": true,
      "loc": "fs/locks.c:1444",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375456,
      "name": "locks_mandatory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t start</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t end</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned char type</code>
</li>
<li>
<b>Param removed. </b>
<code>int read_write</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
<li>
<b>Param reordered. </b>
<code>read_write, inode, filp, offset, count</code> ➡️ <code>inode, filp, start, end, type</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int locks_mandatory_area(struct inode * inode, struct file * filp, loff_t start, loff_t end, unsigned char type)
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
