# Function: <code>__configfs_open_file</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582452288,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452288,
      "name": "__configfs_open_file.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582551840,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551840,
      "name": "__configfs_open_file.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582857776,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582857776,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930800,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930800,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582958464,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:354",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958464,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:290",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294048,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071592249169,
      "name": "__configfs_open_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:290",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800192,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071594030238,
      "name": "__configfs_open_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:290",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420688,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071596063944,
      "name": "__configfs_open_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:290",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649328,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    },
    {
      "addr": 18446744071596587862,
      "name": "__configfs_open_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:290",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584881728,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    },
    {
      "addr": 18446744071597493690,
      "name": "__configfs_open_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494191392,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494191392,
      "name": "__configfs_open_file.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227626220,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227626220,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287882912,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287882912,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273653114,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273653114,
      "name": "__configfs_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582520576,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520576,
      "name": "__configfs_open_file.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457744,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457744,
      "name": "__configfs_open_file.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582511056,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511056,
      "name": "__configfs_open_file.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__configfs_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582591696,
      "name": "__configfs_open_file",
      "external": false,
      "loc": "fs/configfs/file.c:356",
      "file": "fs/configfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_open_bin_file",
        "fs/configfs/file.c:configfs_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582591696,
      "name": "__configfs_open_file.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int __configfs_open_file(struct inode * inode, struct file * file, int type)
```
</details>
</li>
</ul>
