# Function: <code>submit_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int submit_bh(int rw, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581223776,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3055",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/bitmap.c:read_page",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223776,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581391818,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3113",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/bitmap.c:read_page",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390624,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581470234,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3154",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/bitmap.c:read_page",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469040,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581525754,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3141",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/bitmap.c:read_page",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524528,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581668074,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3109",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666880,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581831502,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3080",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830320,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581918750,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3092",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917568,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055957,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3099",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054720,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582133733,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132416,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582374003,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3077",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357536,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582430307,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3058",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414256,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457091,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3079",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441456,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582780707,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3058",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764272,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583319995,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3043",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:bh_submit_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314096,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void submit_bh(blk_opf_t opf, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583904746,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:2705",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900528,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void submit_bh(blk_opf_t opf, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584130682,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:2843",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/mmp.c:write_mmp_block_thawed",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123952,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void submit_bh(blk_opf_t opf, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584347690,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:2803",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/mmp.c:write_mmp_block_thawed",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:write_file_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340688,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493678372,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493676504,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227210388,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227208584,
      "name": "submit_bh",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287291116,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287278432,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273302626,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273301246,
      "name": "submit_bh",
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582102469,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101152,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582039909,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038592,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582092949,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091632,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int submit_bh(int op, int op_flags, struct buffer_head * bh)
```

```json
{
  "name": "submit_bh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582165701,
      "name": "submit_bh",
      "external": true,
      "loc": "fs/buffer.c:3076",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164400,
      "name": "submit_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, bh</code> ➡️ <code>op, op_flags, bh</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, op_flags, bh</code> ➡️ <code>opf, bh</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
