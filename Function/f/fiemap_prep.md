# Function: <code>fiemap_prep</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
```

```json
{
  "name": "fiemap_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167552,
      "name": "fiemap_prep",
      "external": true,
      "loc": "fs/ioctl.c:164",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__generic_block_fiemap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167552,
      "name": "fiemap_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
```

```json
{
  "name": "fiemap_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582214080,
      "name": "fiemap_prep",
      "external": true,
      "loc": "fs/ioctl.c:164",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__generic_block_fiemap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214080,
      "name": "fiemap_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
```

```json
{
  "name": "fiemap_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239488,
      "name": "fiemap_prep",
      "external": true,
      "loc": "fs/ioctl.c:167",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__generic_block_fiemap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239488,
      "name": "fiemap_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
```

```json
{
  "name": "fiemap_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558208,
      "name": "fiemap_prep",
      "external": true,
      "loc": "fs/ioctl.c:167",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558208,
      "name": "fiemap_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
```

```json
{
  "name": "fiemap_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583086992,
      "name": "fiemap_prep",
      "external": true,
      "loc": "fs/ioctl.c:167",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086992,
      "name": "fiemap_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
```

```json
{
  "name": "fiemap_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583654752,
      "name": "fiemap_prep",
      "external": true,
      "loc": "fs/ioctl.c:167",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583654752,
      "name": "fiemap_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
```

```json
{
  "name": "fiemap_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871584,
      "name": "fiemap_prep",
      "external": true,
      "loc": "fs/ioctl.c:167",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871584,
      "name": "fiemap_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
```

```json
{
  "name": "fiemap_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584078608,
      "name": "fiemap_prep",
      "external": true,
      "loc": "fs/ioctl.c:168",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/extents.c:ext4_get_es_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078608,
      "name": "fiemap_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int fiemap_prep(struct inode * inode, struct fiemap_extent_info * fieinfo, u64 start, u64 * len, u32 supported_flags)
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
