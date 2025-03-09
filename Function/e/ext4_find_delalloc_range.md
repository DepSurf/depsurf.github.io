# Function: <code>ext4_find_delalloc_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode * inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end)
```

```json
{
  "name": "ext4_find_delalloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759616,
      "name": "ext4_find_delalloc_range",
      "external": true,
      "loc": "fs/ext4/extents.c:3832",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:ext4_find_delalloc_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759616,
      "name": "ext4_find_delalloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode * inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end)
```

```json
{
  "name": "ext4_find_delalloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954208,
      "name": "ext4_find_delalloc_range",
      "external": true,
      "loc": "fs/ext4/extents.c:3846",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:ext4_find_delalloc_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954208,
      "name": "ext4_find_delalloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int ext4_find_delalloc_range(struct inode * inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end)
```

```json
{
  "name": "ext4_find_delalloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582044336,
      "name": "ext4_find_delalloc_range",
      "external": true,
      "loc": "fs/ext4/extents.c:3838",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:ext4_find_delalloc_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044336,
      "name": "ext4_find_delalloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode * inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end)
```

```json
{
  "name": "ext4_find_delalloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581907008,
      "name": "ext4_find_delalloc_range",
      "external": true,
      "loc": "fs/ext4/extents.c:3833",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:ext4_find_delalloc_cluster",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907008,
      "name": "ext4_find_delalloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode * inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end)
```

```json
{
  "name": "ext4_find_delalloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057200,
      "name": "ext4_find_delalloc_range",
      "external": true,
      "loc": "fs/ext4/extents.c:3833",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:ext4_find_delalloc_cluster",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057200,
      "name": "ext4_find_delalloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ext4_find_delalloc_range(struct inode * inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end)
```

```json
{
  "name": "ext4_find_delalloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245248,
      "name": "ext4_find_delalloc_range",
      "external": true,
      "loc": "fs/ext4/extents.c:3827",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:get_reserved_cluster_alloc",
        "fs/ext4/extents.c:ext4_find_delalloc_cluster",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245248,
      "name": "ext4_find_delalloc_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int ext4_find_delalloc_range(struct inode * inode, ext4_lblk_t lblk_start, ext4_lblk_t lblk_end)
```
</details>
</li>
</ul>
