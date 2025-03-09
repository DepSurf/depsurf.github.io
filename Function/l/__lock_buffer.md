# Function: <code>__lock_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581219504,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:68",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:nobh_write_begin"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219504,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581397886,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:69",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383808,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581476221,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461952,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581531188,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517200,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581673822,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659552,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581837389,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:63",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821536,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581924653,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:63",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909152,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582062035,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045936,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582139827,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123712,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582374134,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:67",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356896,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582430438,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:67",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_update_super_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415248,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457222,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:67",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440800,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582780838,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:67",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764752,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583322247,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:67",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313648,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583904843,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:67",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_folio",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:__ext4_xattr_check_block",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901424,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584130779,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:68",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_folio",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_getuuid",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:check_xattrs",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124928,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584347787,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:69",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_folio",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_getuuid",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:check_xattrs",
        "fs/ext4/fast_commit.c:ext4_fc_submit_bh",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339920,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493684400,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493662496,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227217456,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227198456,
      "name": "__lock_buffer",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287291312,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287267200,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273307890,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273293490,
      "name": "__lock_buffer",
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582108563,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092448,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582046003,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029968,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582099043,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082928,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __lock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__lock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582172025,
      "name": "__lock_buffer",
      "external": true,
      "loc": "fs/buffer.c:64",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156496,
      "name": "__lock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
