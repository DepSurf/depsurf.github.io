# Function: <code>ext4_fiemap_check_ranges</code>

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
int ext4_fiemap_check_ranges(struct inode * inode, u64 start, u64 * len)
```

```json
{
  "name": "ext4_fiemap_check_ranges",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582898256,
      "name": "ext4_fiemap_check_ranges",
      "external": false,
      "loc": "fs/ext4/extents.c:4861",
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
      "addr": 18446744071582898256,
      "name": "ext4_fiemap_check_ranges",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int ext4_fiemap_check_ranges(struct inode * inode, u64 start, u64 * len)
```

```json
{
  "name": "ext4_fiemap_check_ranges",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970176,
      "name": "ext4_fiemap_check_ranges",
      "external": false,
      "loc": "fs/ext4/extents.c:4870",
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
      "addr": 18446744071582970176,
      "name": "ext4_fiemap_check_ranges",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int ext4_fiemap_check_ranges(struct inode * inode, u64 start, u64 * len)
```

```json
{
  "name": "ext4_fiemap_check_ranges",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995968,
      "name": "ext4_fiemap_check_ranges",
      "external": false,
      "loc": "fs/ext4/extents.c:4876",
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
      "addr": 18446744071582995968,
      "name": "ext4_fiemap_check_ranges",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int ext4_fiemap_check_ranges(struct inode * inode, u64 start, u64 * len)
```

```json
{
  "name": "ext4_fiemap_check_ranges",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583333696,
      "name": "ext4_fiemap_check_ranges",
      "external": false,
      "loc": "fs/ext4/extents.c:4914",
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
      "addr": 18446744071583333696,
      "name": "ext4_fiemap_check_ranges",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fiemap_check_ranges",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583876528,
      "name": "ext4_fiemap_check_ranges",
      "external": false,
      "loc": "fs/ext4/extents.c:4917",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
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
  "name": "ext4_fiemap_check_ranges",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584500928,
      "name": "ext4_fiemap_check_ranges",
      "external": false,
      "loc": "fs/ext4/extents.c:4921",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
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
  "name": "ext4_fiemap_check_ranges",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584729440,
      "name": "ext4_fiemap_check_ranges",
      "external": false,
      "loc": "fs/ext4/extents.c:4920",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
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
  "name": "ext4_fiemap_check_ranges",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584962064,
      "name": "ext4_fiemap_check_ranges",
      "external": false,
      "loc": "fs/ext4/extents.c:4955",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_get_es_cache",
        "fs/ext4/extents.c:ext4_fiemap"
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
int ext4_fiemap_check_ranges(struct inode * inode, u64 start, u64 * len)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int ext4_fiemap_check_ranges(struct inode * inode, u64 start, u64 * len)
```
</details>
</li>
</ul>
