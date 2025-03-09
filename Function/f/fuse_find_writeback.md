# Function: <code>fuse_find_writeback</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct fuse_req * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:338",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090832,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583115568,
      "name": "fuse_find_writeback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195792,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195792,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583526344,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:367",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_range_is_writeback"
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
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583636440,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_range_is_writeback"
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
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583657256,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:394",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_range_is_writeback"
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
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584015880,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:398",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_range_is_writeback"
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
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584597960,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:404",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_range_is_writeback"
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
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585276456,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:404",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_range_is_writeback"
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
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585506936,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:405",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_range_is_writeback"
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
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585743688,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:406",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_range_is_writeback"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494915000,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494915000,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228327172,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228327172,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288781136,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288781136,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274224334,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274224334,
      "name": "fuse_find_writeback",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164528,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164528,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101680,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101680,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583148560,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148560,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_find_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242288,
      "name": "fuse_find_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:366",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_range_is_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242288,
      "name": "fuse_find_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct fuse_req * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct fuse_req *</code> ➡️ <code>struct fuse_writepage_args *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct fuse_writepage_args * fuse_find_writeback(struct fuse_inode * fi, long unsigned int idx_from, long unsigned int idx_to)
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
