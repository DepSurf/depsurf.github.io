# Function: <code>ext4_inode_block_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_inode_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582886928,
      "name": "ext4_inode_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:328",
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
      "addr": 18446744071582886928,
      "name": "ext4_inode_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_inode_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959840,
      "name": "ext4_inode_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:300",
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
      "addr": 18446744071582959840,
      "name": "ext4_inode_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_inode_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985760,
      "name": "ext4_inode_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:300",
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
      "addr": 18446744071582985760,
      "name": "ext4_inode_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_inode_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583321616,
      "name": "ext4_inode_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:300",
      "file": "fs/ext4/block_validity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_check_blockref",
        "fs/ext4/extents.c:ext4_valid_extent_entries",
        "fs/ext4/extents.c:ext4_valid_extent_entries",
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
      "addr": 18446744071583321616,
      "name": "ext4_inode_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_inode_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583829892,
      "name": "ext4_inode_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:343",
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
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829744,
      "name": "ext4_inode_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_inode_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584452916,
      "name": "ext4_inode_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:343",
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
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452752,
      "name": "ext4_inode_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_inode_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584681860,
      "name": "ext4_inode_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:343",
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
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681696,
      "name": "ext4_inode_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```

```json
{
  "name": "ext4_inode_block_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584914628,
      "name": "ext4_inode_block_valid",
      "external": true,
      "loc": "fs/ext4/block_validity.c:343",
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
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914464,
      "name": "ext4_inode_block_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_inode_block_valid(struct inode * inode, ext4_fsblk_t start_blk, unsigned int count)
```
</details>
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
