# Function: <code>ext4_lock_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581528076,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2906",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544032,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2906",
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
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581705949,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2906",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783504,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2906",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544032,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071581783504,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581717018,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2944",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741348,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2944",
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
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581908992,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2944",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582012698,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2944",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729808,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071581978336,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581804650,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2922",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581828884,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2922",
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
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581999040,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2922",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102753,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2922",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817408,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582068560,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581876018,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2940",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581952814,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2940",
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
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071582068914,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2940",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks"
      ]
    },
    {
      "addr": 18446744071582215932,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2940",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942656,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071582035952,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582026035,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2897",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101854,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2897",
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
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071582218354,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2897",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
      ]
    },
    {
      "addr": 18446744071582364825,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2897",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091968,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071582186208,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582214307,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2906",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290028,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2906",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071582408164,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2906",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    },
    {
      "addr": 18446744071582555345,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2906",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278336,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071582373648,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582309155,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2933",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582388780,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2933",
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
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071582507588,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2933",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
      ]
    },
    {
      "addr": 18446744071582656587,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:2933",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377024,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071582473280,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582475529,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3013",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582556880,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3013",
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
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071582676692,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3013",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582820069,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3013",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547360,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582574457,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657800,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778740,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923413,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582883636,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3186",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969408,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3186",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071583090340,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3186",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583239941,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3186",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958096,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582956521,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3366",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045049,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3366",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583169300,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3366",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583341781,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3366",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582982441,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3431",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583071076,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3431",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583196121,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3431",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
      ]
    },
    {
      "addr": 18446744071583364693,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3431",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155024,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583318281,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3501",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583409196,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3501",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583539337,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3501",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal"
      ]
    },
    {
      "addr": 18446744071583707605,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3501",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583496016,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583825916,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3464",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583924546,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3464",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072500,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3464",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584261767,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3464",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584448574,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3479",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584550595,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3479",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705505,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3479",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ]
    },
    {
      "addr": 18446744071584911431,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3479",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655664,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584677252,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3458",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584779362,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3458",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584928945,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3458",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585140228,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3458",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584909587,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3478",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585012066,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3478",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585160497,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3478",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585373012,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3478",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494221788,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494300520,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    },
    {
      "addr": 18446603336494437180,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ]
    },
    {
      "addr": 18446603336494600176,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494300520,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446603336494410560,
      "name": "ext4_lock_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227652516,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227745992,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227882584,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3228043364,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287918652,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288030436,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288198836,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288401944,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273677980,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273751398,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273857410,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273976430,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582543193,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582626536,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582747476,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892149,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582480361,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563704,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684644,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582829301,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582533673,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582616392,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737332,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881045,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
  "name": "ext4_lock_group",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582614436,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699376,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582822612,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582967818,
      "name": "ext4_lock_group",
      "external": false,
      "loc": "fs/ext4/ext4.h:3075",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void ext4_lock_group(struct super_block * sb, ext4_group_t group)
```
</details>
</li>
</ul>
