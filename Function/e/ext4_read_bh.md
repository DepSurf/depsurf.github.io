# Function: <code>ext4_read_bh</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_read_bh(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583321600,
      "name": "ext4_read_bh",
      "external": true,
      "loc": "fs/ext4/super.c:173",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583321600,
      "name": "ext4_read_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int ext4_read_bh(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583344416,
      "name": "ext4_read_bh",
      "external": true,
      "loc": "fs/ext4/super.c:173",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344416,
      "name": "ext4_read_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int ext4_read_bh(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583687152,
      "name": "ext4_read_bh",
      "external": true,
      "loc": "fs/ext4/super.c:170",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687152,
      "name": "ext4_read_bh",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_read_bh(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237520,
      "name": "ext4_read_bh",
      "external": true,
      "loc": "fs/ext4/super.c:189",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237520,
      "name": "ext4_read_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_read_bh(struct buffer_head * bh, blk_opf_t op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584881712,
      "name": "ext4_read_bh",
      "external": true,
      "loc": "fs/ext4/super.c:189",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584881712,
      "name": "ext4_read_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int ext4_read_bh(struct buffer_head * bh, blk_opf_t op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585108912,
      "name": "ext4_read_bh",
      "external": true,
      "loc": "fs/ext4/super.c:189",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108912,
      "name": "ext4_read_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int ext4_read_bh(struct buffer_head * bh, blk_opf_t op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585341248,
      "name": "ext4_read_bh",
      "external": true,
      "loc": "fs/ext4/super.c:190",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341248,
      "name": "ext4_read_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_read_bh(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int op_flags</code> ➡️ <code>blk_opf_t op_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
