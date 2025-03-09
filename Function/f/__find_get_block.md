# Function: <code>__find_get_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581219568,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1365",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219568,
      "name": "__find_get_block",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581386112,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1355",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386112,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581465104,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1355",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465104,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581519296,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1350",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519296,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581661792,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1310",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661792,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1281",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839009,
      "name": "__find_get_block.cold.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071581826304,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581912646,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1289",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926273,
      "name": "__find_get_block.cold.64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071581912384,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 714
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582049783,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063720,
      "name": "__find_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071582049520,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582127639,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141557,
      "name": "__find_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071582127376,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582365808,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1323",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:recently_deleted",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365808,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582424640,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1322",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:recently_deleted",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582424640,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582452592,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1327",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452592,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582779248,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1302",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779248,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583322816,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1301",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322816,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583908368,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1301",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908368,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584138288,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1413",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138288,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584354416,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1395",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354416,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493669736,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493669736,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227202284,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227202284,
      "name": "__find_get_block",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287270400,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287270400,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273296162,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273296162,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 786
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582096375,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110293,
      "name": "__find_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071582096112,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582033830,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047733,
      "name": "__find_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071582033584,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582086855,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100773,
      "name": "__find_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071582086592,
      "name": "__find_get_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_head * __find_get_block(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__find_get_block",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582159564,
      "name": "__find_get_block",
      "external": true,
      "loc": "fs/buffer.c:1290",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173643,
      "name": "__find_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071582159280,
      "name": "__find_get_block",
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
