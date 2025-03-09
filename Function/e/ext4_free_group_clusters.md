# Function: <code>ext4_free_group_clusters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581694912,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:199",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694912,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581916048,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:228",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886656,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582006061,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:230",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975664,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582220897,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:232",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191808,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582369601,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:232",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340480,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582560638,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:232",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529968,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582659570,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:255",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631056,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582834837,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:256",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803680,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582939963,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907040,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583239143,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:231",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220576,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583340972,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:320",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322496,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583363884,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:320",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345312,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583706797,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:317",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689136,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584260913,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:336",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239792,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584910545,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:330",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884176,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585139346,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:330",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111376,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585372130,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:338",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343824,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494613760,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494582032,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228056664,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228025028,
      "name": "ext4_free_group_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288417676,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288380080,
      "name": "ext4_free_group_clusters",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273990622,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273961756,
      "name": "ext4_free_group_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582908699,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875776,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582845851,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812928,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582897300,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864656,
      "name": "ext4_free_group_clusters",
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
__u32 ext4_free_group_clusters(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_group_clusters",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582984372,
      "name": "ext4_free_group_clusters",
      "external": true,
      "loc": "fs/ext4/super.c:251",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951312,
      "name": "ext4_free_group_clusters",
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
