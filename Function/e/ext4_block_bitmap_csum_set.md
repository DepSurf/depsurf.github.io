# Function: <code>ext4_block_bitmap_csum_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534080,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:82",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534080,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581719712,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:82",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719712,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807344,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:82",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807344,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878240,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:82",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878240,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028304,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028304,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582216512,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216512,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311360,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311360,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582477696,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477696,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582576624,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582576624,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582885248,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885248,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582958160,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958160,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984080,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984080,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583319920,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583319920,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583827664,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827664,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584450416,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450416,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void ext4_block_bitmap_csum_set(struct super_block * sb, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679360,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:80",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679360,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void ext4_block_bitmap_csum_set(struct super_block * sb, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912128,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:80",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912128,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494225384,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494225384,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227655344,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227655344,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287922224,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287922224,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273680316,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273680316,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545360,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545360,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482528,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482528,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535840,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535840,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void ext4_block_bitmap_csum_set(struct super_block * sb, ext4_group_t group, struct ext4_group_desc * gdp, struct buffer_head * bh)
```

```json
{
  "name": "ext4_block_bitmap_csum_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616608,
      "name": "ext4_block_bitmap_csum_set",
      "external": true,
      "loc": "fs/ext4/bitmap.c:83",
      "file": "fs/ext4/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616608,
      "name": "ext4_block_bitmap_csum_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
<b>Param removed. </b>
<code>ext4_group_t group</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, group, gdp, bh</code> ➡️ <code>sb, gdp, bh</code>
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
