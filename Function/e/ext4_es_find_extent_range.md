# Function: <code>ext4_es_find_extent_range</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361616,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_fiemap",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361616,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529616,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529616,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630624,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630624,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939648,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_iomap_begin_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939648,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014080,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014080,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583039616,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583039616,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583377056,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377056,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583889808,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583889808,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584514704,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:307",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584514704,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584742960,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:307",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742960,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584975584,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:308",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_determine_insert_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584975584,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494280536,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494280536,
      "name": "ext4_es_find_extent_range",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227715072,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227715072,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287993248,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287993248,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273726788,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273726788,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599360,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599360,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582536528,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536528,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589472,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589472,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "ext4_es_find_extent_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671104,
      "name": "ext4_es_find_extent_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:309",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/extents.c:ext4_fill_fiemap_extents",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671104,
      "name": "ext4_es_find_extent_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void ext4_es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
