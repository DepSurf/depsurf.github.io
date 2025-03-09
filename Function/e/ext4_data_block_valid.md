# Function: <code>ext4_data_block_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581820064,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:196",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820064,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015792,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:196",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015792,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105840,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:196",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105840,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879488,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:196",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879488,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029552,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:197",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029552,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217680,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:197",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217680,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312528,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:197",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312528,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478400,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:247",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478400,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582578642,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_check_blockref"
      ],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582578480,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494227684,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_check_blockref"
      ],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494227480,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227657876,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_check_blockref"
      ],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227657696,
      "name": "ext4_data_block_valid",
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287925364,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_check_blockref"
      ],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287925120,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273682328,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_check_blockref"
      ],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273682134,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582547378,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_check_blockref"
      ],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547216,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582484546,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_check_blockref"
      ],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484384,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582537858,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/block_validity.c:ext4_check_blockref"
      ],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582537696,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_data_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582618448,
      "name": "ext4_data_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:342",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618448,
      "name": "ext4_data_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int ext4_data_block_valid(struct ext4_sb_info * sbi, ext4_fsblk_t start_blk, unsigned int count)
```
</details>
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
