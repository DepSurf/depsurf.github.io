# Function: <code>ext4_es_insert_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842656,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:690",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842656,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582037536,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:690",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037536,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127648,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:690",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127648,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926816,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:690",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926816,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077120,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:691",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077120,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582265040,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:690",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265040,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582362048,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362048,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530048,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530048,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582631072,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631072,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940320,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940320,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014752,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:815",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014752,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583040288,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:815",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040288,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583377728,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:815",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377728,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890720,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:815",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890720,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515664,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:812",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515664,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
void ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743840,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:833",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743840,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
void ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584976464,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:847",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_determine_insert_hole",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584976464,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494281384,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494281384,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227715708,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227715708,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287994000,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287994000,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273727264,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273727264,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599808,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599808,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582536976,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536976,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589920,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589920,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int ext4_es_insert_extent(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, ext4_fsblk_t pblk, unsigned int status)
```

```json
{
  "name": "ext4_es_insert_extent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671616,
      "name": "ext4_es_insert_extent",
      "external": true,
      "loc": "fs/ext4/extents_status.c:806",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_zeroout_es",
        "fs/ext4/extents.c:ext4_ext_put_gap_in_cache",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671616,
      "name": "ext4_es_insert_extent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 731
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
