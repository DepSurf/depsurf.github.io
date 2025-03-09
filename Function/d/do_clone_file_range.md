# Function: <code>do_clone_file_range</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581312654,
      "name": "do_clone_file_range",
      "external": false,
      "loc": "include/linux/fs.h:1750",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:ioctl_file_clone"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581364321,
      "name": "do_clone_file_range",
      "external": false,
      "loc": "include/linux/fs.h:2687",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:ioctl_file_clone"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581505773,
      "name": "do_clone_file_range",
      "external": false,
      "loc": "include/linux/fs.h:2748",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:ioctl_file_clone"
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
  "name": "do_clone_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581662348,
      "name": "do_clone_file_range",
      "external": false,
      "loc": "include/linux/fs.h:2770",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:ioctl_file_clone"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649984,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:1974",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649984,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767344,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2055",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767344,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581839552,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839552,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063936,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2137",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063936,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582410080,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:375",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410080,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436848,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:375",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436848,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759600,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:363",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759600,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583310672,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:358",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583310672,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583895600,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:367",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583895600,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584117392,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/remap_range.c:370",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584117392,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
    }
  ]
}
```
</details>
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493304664,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493304664,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226906372,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226906372,
      "name": "do_clone_file_range",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286843504,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286843504,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273048108,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273048108,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581808288,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808288,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581745952,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745952,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581799600,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799600,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "do_clone_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581868768,
      "name": "do_clone_file_range",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868768,
      "name": "do_clone_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
loff_t do_clone_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t len, unsigned int remap_flags)
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
