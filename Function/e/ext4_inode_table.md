# Function: <code>ext4_inode_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581694864,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:191",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694864,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581908891,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:220",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886608,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581998940,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:222",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975616,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215824,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:224",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191760,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582364718,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:224",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340432,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582555248,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:224",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529920,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582656491,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:247",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631008,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582824082,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:248",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803632,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582927442,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906992,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583222966,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:223",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:recently_deleted",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220528,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583324854,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:312",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:recently_deleted",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322448,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583347588,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:312",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345264,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691525,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:309",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689088,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584242605,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:328",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239744,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584887501,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:322",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884112,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585114653,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:322",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111312,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585347069,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:330",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343760,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494604332,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494581960,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228047572,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228024976,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288406604,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288380032,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273979930,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273961692,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582896178,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875728,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582833330,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812880,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582885074,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864608,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ext4_fsblk_t ext4_inode_table(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582971826,
      "name": "ext4_inode_table",
      "external": true,
      "loc": "fs/ext4/super.c:243",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951264,
      "name": "ext4_inode_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
