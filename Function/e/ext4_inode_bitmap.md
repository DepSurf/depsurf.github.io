# Function: <code>ext4_inode_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581694816,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:183",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694816,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581908800,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:212",
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
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886560,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581998849,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:214",
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
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975568,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215725,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:216",
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
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191712,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582364621,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:216",
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
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340384,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582555161,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:216",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529872,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582656404,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:239",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630960,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582824009,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:240",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803584,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582927369,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906944,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583222891,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:215",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220480,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583324779,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:304",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322400,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583347514,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:304",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345216,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691440,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:301",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689040,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584242522,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:320",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239696,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584887418,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:314",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884048,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585114570,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:314",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111248,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585346986,
      "name": "ext4_inode_bitmap",
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
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343696,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494604220,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494581888,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228047376,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228024924,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288406580,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288379984,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273979914,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273961628,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582896105,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875680,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582833257,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812832,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582885001,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864560,
      "name": "ext4_inode_bitmap",
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
ext4_fsblk_t ext4_inode_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_inode_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582971753,
      "name": "ext4_inode_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951216,
      "name": "ext4_inode_bitmap",
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
