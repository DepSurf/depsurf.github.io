# Function: <code>ext4_es_find_delayed_extent_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_es_find_delayed_extent_range(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_delayed_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842176,
      "name": "ext4_es_find_delayed_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:244",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek",
        "fs/ext4/file.c:ext4_llseek",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_find_delalloc_range",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842176,
      "name": "ext4_es_find_delayed_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void ext4_es_find_delayed_extent_range(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_delayed_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582037104,
      "name": "ext4_es_find_delayed_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:244",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_get_next_extent",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_find_delalloc_range",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037104,
      "name": "ext4_es_find_delayed_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
void ext4_es_find_delayed_extent_range(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_delayed_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127216,
      "name": "ext4_es_find_delayed_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:244",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_get_next_extent",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_find_delalloc_range",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127216,
      "name": "ext4_es_find_delayed_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
void ext4_es_find_delayed_extent_range(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_delayed_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926400,
      "name": "ext4_es_find_delayed_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:244",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_find_delalloc_range",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_get_next_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926400,
      "name": "ext4_es_find_delayed_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void ext4_es_find_delayed_extent_range(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_delayed_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582076688,
      "name": "ext4_es_find_delayed_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:245",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_find_delalloc_range",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076688,
      "name": "ext4_es_find_delayed_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
void ext4_es_find_delayed_extent_range(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_delayed_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264640,
      "name": "ext4_es_find_delayed_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:244",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_find_delalloc_range",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264640,
      "name": "ext4_es_find_delayed_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
void ext4_es_find_delayed_extent_range(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```
</details>
</li>
</ul>
