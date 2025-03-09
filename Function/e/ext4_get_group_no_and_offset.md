# Function: <code>ext4_get_group_no_and_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581528925,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:52",
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
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528976,
      "name": "ext4_get_group_no_and_offset",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581718258,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:52",
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
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714592,
      "name": "ext4_get_group_no_and_offset",
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581805890,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:52",
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
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802224,
      "name": "ext4_get_group_no_and_offset",
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581876914,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:52",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873504,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582026302,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023504,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215485,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211648,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582310333,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306496,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582476652,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472864,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582575580,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571792,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882919,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880272,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582955799,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953056,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582981719,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978960,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583314768,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_get_group_number"
      ],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592250094,
      "name": "ext4_get_group_no_and_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583314800,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583822140,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_get_group_number"
      ],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594031154,
      "name": "ext4_get_group_no_and_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583822176,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584444492,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_get_group_number"
      ],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596064707,
      "name": "ext4_get_group_no_and_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584444544,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584672668,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_get_group_number"
      ],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks_simple",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596588560,
      "name": "ext4_get_group_no_and_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584672720,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584905388,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:54",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_get_group_number"
      ],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks_simple",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597494388,
      "name": "ext4_get_group_no_and_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584905440,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494223524,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494218632,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227649264,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227649264,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287920512,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287914688,
      "name": "ext4_get_group_no_and_offset",
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273679250,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273675430,
      "name": "ext4_get_group_no_and_offset",
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582544316,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540528,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582481484,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477696,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582534796,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531008,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void ext4_get_group_no_and_offset(struct super_block * sb, ext4_fsblk_t blocknr, ext4_group_t * blockgrpp, ext4_grpblk_t * offsetp)
```

```json
{
  "name": "ext4_get_group_no_and_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582615574,
      "name": "ext4_get_group_no_and_offset",
      "external": true,
      "loc": "fs/ext4/balloc.c:53",
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
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_use_inode_pa",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:verify_group_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611680,
      "name": "ext4_get_group_no_and_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
