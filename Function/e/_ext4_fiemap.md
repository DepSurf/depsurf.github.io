# Function: <code>_ext4_fiemap</code>

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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599712,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599712,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494249792,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494249792,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227681636,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227681636,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287954336,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287954336,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273700304,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273700304,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568448,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568448,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582505616,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582505616,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558560,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558560,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```

```json
{
  "name": "_ext4_fiemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582639776,
      "name": "_ext4_fiemap",
      "external": false,
      "loc": "fs/ext4/extents.c:5102",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639776,
      "name": "_ext4_fiemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int _ext4_fiemap(struct inode * inode, struct fiemap_extent_info * fieinfo, __u64 start, __u64 len, int (*)(struct inode *, ext4_lblk_t, ext4_lblk_t, struct fiemap_extent_info *) fill)
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
