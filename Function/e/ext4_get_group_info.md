# Function: <code>ext4_get_group_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581527981,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2772",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544224,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2772",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_init_inode_table"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581786557,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2772",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544224,
      "name": "ext4_get_group_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715525,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2807",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740972,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2807",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    },
    {
      "addr": 18446744071582012460,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2807",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730000,
      "name": "ext4_get_group_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581803157,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2785",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581828508,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2785",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    },
    {
      "addr": 18446744071582102524,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2785",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817600,
      "name": "ext4_get_group_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874459,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2803",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    },
    {
      "addr": 18446744071581952444,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2803",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    },
    {
      "addr": 18446744071582066668,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2803",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872528,
      "name": "ext4_get_group_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071581941136,
      "name": "ext4_get_group_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582024459,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2760",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101462,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2760",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    },
    {
      "addr": 18446744071582216127,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2760",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090096,
      "name": "ext4_get_group_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582212621,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2765",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582289676,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2765",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406079,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2765",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582544075,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2765",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582307469,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2792",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582388428,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2792",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505343,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2792",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582645211,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2792",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582473871,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582556527,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582676326,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817995,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582572797,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657413,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778358,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582921163,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582881302,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3045",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969605,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3045",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089958,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3045",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583237995,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3045",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582954163,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3219",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045242,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3219",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583168900,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3219",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583339773,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3219",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582980065,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3281",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070935,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3281",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583195734,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3281",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583362669,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3281",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583316022,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3351",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583406443,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3351",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538953,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3351",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705517,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3351",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493920,
      "name": "ext4_get_group_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071592260072,
      "name": "ext4_get_group_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583823539,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3314",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583921595,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3314",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072021,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3314",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584259532,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3314",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584446003,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3327",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584547634,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3327",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584704725,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3327",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584909068,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:3327",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_info",
      "external": true,
      "loc": "fs/ext4/balloc.c:324",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596588635,
      "name": "ext4_get_group_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584673136,
      "name": "ext4_get_group_info",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_info",
      "external": true,
      "loc": "fs/ext4/balloc.c:326",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597494463,
      "name": "ext4_get_group_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584905856,
      "name": "ext4_get_group_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494219860,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494310184,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494444560,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494597940,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227650708,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 3227745540,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227882084,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 3228040608,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287916164,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288029896,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288198264,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288399044,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273676460,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273751098,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273857096,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273974384,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582541533,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582626149,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582747094,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582889899,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582478701,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563317,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684262,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582827051,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582532013,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582616005,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736950,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878795,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_group_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582612759,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_count_free_clusters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582698965,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582822206,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582965500,
      "name": "ext4_get_group_info",
      "external": false,
      "loc": "fs/ext4/ext4.h:2934",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct ext4_group_info * ext4_get_group_info(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
