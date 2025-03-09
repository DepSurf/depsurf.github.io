# Function: <code>generic_copy_file_range</code>

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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581777530,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763552,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581849754,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835760,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582075002,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1699",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058976,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124418,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1384",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108224,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582149139,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1389",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133168,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582465971,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1380",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449824,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582986350,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1394",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582968672,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583546449,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1387",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528016,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583762420,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1386",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743440,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493316000,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493299368,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226913844,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226902336,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286856504,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286838608,
      "name": "generic_copy_file_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273051888,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273043814,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581818490,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804496,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581756154,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742160,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581809802,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795808,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581879018,
      "name": "generic_copy_file_range",
      "external": true,
      "loc": "fs/read_write.c:1615",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864976,
      "name": "generic_copy_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
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
ssize_t generic_copy_file_range(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t len, unsigned int flags)
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
