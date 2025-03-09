# Function: <code>ext4_get_group_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581528896,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:34",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_discard_preallocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528896,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581717568,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:34",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714512,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581805200,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:34",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802144,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581876495,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:34",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873440,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582026282,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023440,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582214585,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211584,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582309433,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306432,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582475800,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472800,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582574728,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571728,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882909,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880208,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582955789,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952992,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582981709,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978896,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592250031,
      "name": "ext4_get_group_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583314704,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594031091,
      "name": "ext4_get_group_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583822064,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596064644,
      "name": "ext4_get_group_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584444416,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596588497,
      "name": "ext4_get_group_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584672592,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:36",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/ioctl.c:ext4_update_superblocks_fn",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597494325,
      "name": "ext4_get_group_number.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584905312,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494222396,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494218528,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227649404,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227649404,
      "name": "ext4_get_group_number",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287919028,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287914608,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273678246,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273675332,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582543464,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540464,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582480632,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477632,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582533944,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530944,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block * sb, ext4_fsblk_t block)
```

```json
{
  "name": "ext4_get_group_number",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582614707,
      "name": "ext4_get_group_number",
      "external": true,
      "loc": "fs/ext4/balloc.c:35",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611616,
      "name": "ext4_get_group_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
