# Function: <code>ext4_read_bh_nowait</code>

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
void ext4_read_bh_nowait(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583321488,
      "name": "ext4_read_bh_nowait",
      "external": true,
      "loc": "fs/ext4/super.c:161",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583321488,
      "name": "ext4_read_bh_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void ext4_read_bh_nowait(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583344304,
      "name": "ext4_read_bh_nowait",
      "external": true,
      "loc": "fs/ext4/super.c:161",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344304,
      "name": "ext4_read_bh_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void ext4_read_bh_nowait(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh_nowait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583687056,
      "name": "ext4_read_bh_nowait",
      "external": true,
      "loc": "fs/ext4/super.c:158",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687056,
      "name": "ext4_read_bh_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void ext4_read_bh_nowait(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh_nowait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237392,
      "name": "ext4_read_bh_nowait",
      "external": true,
      "loc": "fs/ext4/super.c:177",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237392,
      "name": "ext4_read_bh_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void ext4_read_bh_nowait(struct buffer_head * bh, blk_opf_t op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh_nowait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584881568,
      "name": "ext4_read_bh_nowait",
      "external": true,
      "loc": "fs/ext4/super.c:177",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584881568,
      "name": "ext4_read_bh_nowait",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void ext4_read_bh_nowait(struct buffer_head * bh, blk_opf_t op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh_nowait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585108768,
      "name": "ext4_read_bh_nowait",
      "external": true,
      "loc": "fs/ext4/super.c:177",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108768,
      "name": "ext4_read_bh_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void ext4_read_bh_nowait(struct buffer_head * bh, blk_opf_t op_flags, bh_end_io_t * end_io)
```

```json
{
  "name": "ext4_read_bh_nowait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585341104,
      "name": "ext4_read_bh_nowait",
      "external": true,
      "loc": "fs/ext4/super.c:178",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341104,
      "name": "ext4_read_bh_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void ext4_read_bh_nowait(struct buffer_head * bh, int op_flags, bh_end_io_t * end_io)
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
