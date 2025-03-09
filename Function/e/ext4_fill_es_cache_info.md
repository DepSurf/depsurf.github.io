# Function: <code>ext4_fill_es_cache_info</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582586576,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586576,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582896560,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2139",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582896560,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582968480,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2138",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582968480,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583028174,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2141",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_get_es_cache"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2179",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331072,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071592251124,
      "name": "ext4_fill_es_cache_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2178",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840624,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071594032208,
      "name": "ext4_fill_es_cache_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2185",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464048,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071596065493,
      "name": "ext4_fill_es_cache_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2185",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692944,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071596589415,
      "name": "ext4_fill_es_cache_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2185",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925632,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071597495199,
      "name": "ext4_fill_es_cache_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494236336,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494236336,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227669128,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227669128,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287940240,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287940240,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273691058,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273691058,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555312,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555312,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582492480,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492480,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545424,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545424,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```

```json
{
  "name": "ext4_fill_es_cache_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582626544,
      "name": "ext4_fill_es_cache_info",
      "external": false,
      "loc": "fs/ext4/extents.c:2318",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626544,
      "name": "ext4_fill_es_cache_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```
</details>
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
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_fill_es_cache_info(struct inode * inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info * fieinfo)
```
</details>
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
