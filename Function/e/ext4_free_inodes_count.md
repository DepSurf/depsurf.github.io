# Function: <code>ext4_free_inodes_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581694960,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:207",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_count_free_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694960,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581915994,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:236",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886704,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582006008,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:238",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975712,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582220841,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:240",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191856,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582369548,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:240",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340528,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582560595,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:240",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530016,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582659527,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:263",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631104,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582834794,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:264",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803728,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582939924,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907088,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583239112,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:239",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220624,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583340940,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:328",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322544,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583363852,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:328",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345360,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583706765,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:325",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689184,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584260881,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:344",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239840,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584910513,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:338",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884240,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585139314,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:338",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111440,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585372098,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:346",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343888,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494613712,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494582104,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228056604,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228025076,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288417620,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288380144,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273990580,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273961828,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582908660,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875824,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582845812,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812976,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582897261,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864704,
      "name": "ext4_free_inodes_count",
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
__u32 ext4_free_inodes_count(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_free_inodes_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582984331,
      "name": "ext4_free_inodes_count",
      "external": true,
      "loc": "fs/ext4/super.c:259",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951360,
      "name": "ext4_free_inodes_count",
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
