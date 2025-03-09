# Function: <code>lock_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880652,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581221669,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:nobh_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531342,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545755,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557758,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699232,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724530,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749897,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825359,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831736,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847780,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859434,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581893863,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581899737,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909590,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931828,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581008311,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581397267,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/buffer.c:__block_write_full_page"
      ]
    },
    {
      "addr": 18446744071581716990,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731548,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743601,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891320,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581919357,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944572,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021297,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027761,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045399,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055195,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582084649,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088707,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096744,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118231,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:356",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383680,
      "name": "lock_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581082343,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581475589,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/buffer.c:__block_write_full_page"
      ]
    },
    {
      "addr": 18446744071581804622,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819148,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831329,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581980728,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009421,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034604,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111393,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117889,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135244,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144827,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582174745,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178795,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186840,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208473,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:359",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461824,
      "name": "lock_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581129611,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581530656,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875914,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897024,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942924,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581957242,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964675,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988720,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582073711,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118881,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197134,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238756,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582261222,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265163,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272774,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582293881,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:360",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581243147,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581673229,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582025914,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047200,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092236,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106298,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113731,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138144,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223151,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268033,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345886,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387623,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410262,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414198,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421926,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582442953,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581396260,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:buffer_migrate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836788,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214279,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582239578,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280723,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294671,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302120,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320869,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412911,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582455981,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535116,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578441,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582600390,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582604815,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612308,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582633001,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581477344,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581924052,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309127,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582335498,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379459,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582393426,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400744,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424437,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512367,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582555508,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582636220,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679184,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582702134,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706533,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714074,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734745,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581592361,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582061416,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582475499,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582501375,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582547992,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582558100,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582571585,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593483,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582681455,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582730204,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808796,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852476,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875002,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879815,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887529,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909033,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581656009,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582139208,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574427,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582601471,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582648797,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582659044,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582672545,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694233,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783615,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582832348,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582912156,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582956636,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981706,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986304,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582994105,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583015593,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583061556,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583074612,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581879800,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582373934,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883606,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899559,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582960812,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970823,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582983541,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583006355,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095772,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144760,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583226478,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272516,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298651,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303964,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310351,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332473,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380996,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583392440,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581923288,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582430238,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582956480,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582971479,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019230,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583035063,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046423,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059141,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079309,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125818,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174727,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583212055,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583225153,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328046,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583373677,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_update_super_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583384198,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413947,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419209,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425888,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583449593,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496884,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583508088,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581951176,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582457022,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582982400,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997270,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045038,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060427,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072348,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085104,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583104325,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150135,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201271,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583239959,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252993,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350494,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402347,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583407030,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583436795,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441376,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583448549,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471785,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583518581,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531144,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582255879,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582780638,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318240,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583335286,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382327,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583398367,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583410584,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583424175,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583444511,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489851,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544392,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595620,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583694674,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583746686,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583751334,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583766599,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583786203,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790806,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583798199,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583825225,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880483,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583888136,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:364",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582722378,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583322166,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583825878,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844551,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583895578,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912919,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583926041,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939670,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583967540,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017554,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584077992,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134465,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584246662,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584303674,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308118,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584326558,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584337206,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/ext4/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349647,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584353973,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362723,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584390456,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584453386,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584464415,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:386",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583253166,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904716,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584448481,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584468487,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520798,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584539445,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584552193,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584566198,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595316,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584648534,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584710792,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584768484,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584892006,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584952167,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:__ext4_xattr_check_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584956486,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584975118,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584986363,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/ext4/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584999781,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585005576,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585013563,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048024,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585121295,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585127706,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:393",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583472570,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130652,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584677166,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697383,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584749646,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584768501,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584780904,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584795270,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821620,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584871883,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_getuuid",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584934712,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991828,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585119047,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585180341,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:check_xattrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585184806,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585203375,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585214379,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/ext4/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585227717,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231652,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585240919,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585271265,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585350559,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585357003,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:406",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583664967,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584347660,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584909501,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584930007,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584982526,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585001588,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585013367,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585028133,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585054581,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585104753,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_getuuid",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585166264,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585223482,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585351399,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585413221,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:check_xattrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585417702,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585436271,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585447339,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/ext4/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585460711,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585464638,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585474172,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503777,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585585278,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585591738,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:397",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493105996,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493684388,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494221748,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494251592,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494301300,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494312108,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494325644,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494351276,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494452808,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494509152,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494588436,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494631676,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494662416,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494671548,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494680084,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494707000,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494762480,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494780064,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226802668,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227216840,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 3227652440,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227683688,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 3227735176,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227747808,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 3227760604,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 3227785108,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 3227888032,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 3227945572,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 3228031128,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 3228076816,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 3228106632,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 3228111908,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 3228120192,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 3228144316,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3228186464,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 3228200372,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286570800,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287290992,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287918600,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287962684,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288017872,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288036672,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288046024,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288080864,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288205704,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288271628,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288387860,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288439864,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288478896,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288484148,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288494560,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288528224,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288595620,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288612044,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272953052,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273307362,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273677950,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273701818,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273742514,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273755008,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273760892,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273780998,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273861584,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273902692,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273966910,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274002928,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274026188,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274030658,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274038536,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274059412,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274102270,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274112006,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581624745,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582107944,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582543163,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570207,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617533,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627780,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582641281,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582662969,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582752351,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582801084,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880892,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925372,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950442,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955040,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962841,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582984329,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583030292,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043348,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581566025,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582045384,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582480331,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507375,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582554701,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582564948,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578449,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582600137,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689519,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738236,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818044,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862524,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887594,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892192,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899993,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582921481,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582967444,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980500,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581616057,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582098424,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582533643,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560319,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607389,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617636,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631137,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582652825,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742207,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582789964,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869772,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582913980,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582939050,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943648,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951449,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582972937,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018900,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031956,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
  "name": "lock_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581684502,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582171369,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614411,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582641535,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689960,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582704130,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714365,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737841,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582827471,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876412,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582956474,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001042,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583027043,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031805,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039872,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583061543,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583108040,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121216,
      "name": "lock_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:362",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void lock_buffer(struct buffer_head * bh)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void lock_buffer(struct buffer_head * bh)
```
</details>
</li>
</ul>
