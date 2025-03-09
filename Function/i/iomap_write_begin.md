# Function: <code>iomap_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, unsigned int flags, struct page * * pagep, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580640,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap.c:110",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580640,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, unsigned int flags, struct page * * pagep, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581665568,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap.c:108",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665568,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581722032,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap.c:110",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581722032,
      "name": "iomap_write_begin.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581867856,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap.c:110",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867856,
      "name": "iomap_write_begin.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582050816,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap.c:120",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050816,
      "name": "iomap_write_begin.constprop.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582143248,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap.c:664",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143248,
      "name": "iomap_write_begin.constprop.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582302144,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302144,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582401168,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582401168,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
int iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, unsigned int flags, struct page * * pagep, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582694608,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:611",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694608,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
int iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, unsigned int flags, struct page * * pagep, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582765472,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:591",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582765472,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, unsigned int flags, struct page * * pagep, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582794480,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:591",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582794480,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int iomap_write_begin(const struct iomap_iter * iter, loff_t pos, unsigned int len, struct page * * pagep)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583119632,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:601",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119632,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int iomap_write_begin(const struct iomap_iter * iter, loff_t pos, size_t len, struct folio * * foliop)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:597",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583609104,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 958
    },
    {
      "addr": 18446744071594026055,
      "name": "iomap_write_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int iomap_write_begin(struct iomap_iter * iter, loff_t pos, size_t len, struct folio * * foliop)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:587",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215344,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
    },
    {
      "addr": 18446744071596061898,
      "name": "iomap_write_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int iomap_write_begin(struct iomap_iter * iter, loff_t pos, size_t len, struct folio * * foliop)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:626",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445040,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
    },
    {
      "addr": 18446744071596586064,
      "name": "iomap_write_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int iomap_write_begin(struct iomap_iter * iter, loff_t pos, size_t len, struct folio * * foliop)
```

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:729",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667552,
      "name": "iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
    },
    {
      "addr": 18446744071597491606,
      "name": "iomap_write_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494003600,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494003600,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227467776,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227467776,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287653952,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287653952,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273518238,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273518238,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582369904,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582369904,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582307600,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307600,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582360384,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582360384,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
  "name": "iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440080,
      "name": "iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:583",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440080,
      "name": "iomap_write_begin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, unsigned int flags, struct page * * pagep, struct iomap * iomap)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, unsigned int flags, struct page * * pagep, struct iomap * iomap)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, unsigned int flags, struct page * * pagep, struct iomap * iomap, struct iomap * srcmap)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iomap_iter * iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap * iomap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap * srcmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, pos, len, flags, pagep, iomap, srcmap</code> ➡️ <code>iter, pos, len, pagep</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * * foliop</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * * pagep</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>size_t len</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct iomap_iter * iter</code> ➡️ <code>struct iomap_iter * iter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
