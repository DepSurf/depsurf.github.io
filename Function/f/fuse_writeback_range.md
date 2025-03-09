# Function: <code>fuse_writeback_range</code>

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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583092192,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3024",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583092192,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583197440,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197440,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583541719,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3183",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583651427,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3230",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583672003,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:2884",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
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
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584030985,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:2915",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
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
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584619140,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:2942",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
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
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585298692,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:2978",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
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
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585529050,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:2955",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
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
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585766202,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:2978",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494916944,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494916944,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228329616,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228329616,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288785488,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288785488,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274226004,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274226004,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583166176,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166176,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583103328,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103328,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583150208,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150208,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```

```json
{
  "name": "fuse_writeback_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583245264,
      "name": "fuse_writeback_range",
      "external": false,
      "loc": "fs/fuse/file.c:3158",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245264,
      "name": "fuse_writeback_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int fuse_writeback_range(struct inode * inode, loff_t start, loff_t end)
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
