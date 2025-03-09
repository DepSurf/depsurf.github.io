# Function: <code>ext4_get_es_cache</code>

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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619376,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619376,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930672,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:4913",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930672,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002384,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:4922",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002384,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583027888,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:4928",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583027888,
      "name": "ext4_get_es_cache",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:4966",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592253601,
      "name": "ext4_get_es_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071583364768,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:4969",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594034610,
      "name": "ext4_get_es_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071583876336,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:4973",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596067836,
      "name": "ext4_get_es_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071584500736,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:4972",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596591476,
      "name": "ext4_get_es_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071584729248,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5007",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597497264,
      "name": "ext4_get_es_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071584961872,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494268680,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494268680,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227701960,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227701960,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287978288,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287978288,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273716952,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273716952,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588112,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588112,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525280,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525280,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582578224,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582578224,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
```

```json
{
  "name": "ext4_get_es_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659664,
      "name": "ext4_get_es_cache",
      "external": true,
      "loc": "fs/ext4/extents.c:5170",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659664,
      "name": "ext4_get_es_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int ext4_get_es_cache(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len)
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
