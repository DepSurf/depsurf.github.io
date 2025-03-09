# Function: <code>unlock_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581214256,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:74",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:ll_rw_block",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214256,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378960,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:75",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378960,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457056,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:76",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457056,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513408,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:76",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513408,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655616,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:76",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655616,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818976,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:69",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818976,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905968,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:69",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905968,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582042848,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582042848,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120688,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120688,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582374103,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:73",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356032,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582430407,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:73",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
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
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_update_super_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412800,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457191,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:73",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
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
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439920,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582780807,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:73",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762608,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583320048,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:73",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:bh_submit_read",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311984,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583904792,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:73",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_folio",
        "mm/migrate.c:__buffer_migrate_folio",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:__ext4_xattr_check_block",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897664,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584130728,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:74",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_folio",
        "mm/migrate.c:__buffer_migrate_folio",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_getuuid",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:check_xattrs",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120784,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584347736,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:75",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_folio",
        "mm/migrate.c:__buffer_migrate_folio",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_getuuid",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_update_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/ext4/super.c:ext4_read_bh_nowait",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:check_xattrs",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/fast_commit.c:ext4_end_buffer_io_sync",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584337760,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493661584,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493661584,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227193728,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227193728,
      "name": "unlock_buffer",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287258208,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287258208,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273302536,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273289020,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089424,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089424,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026944,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026944,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582079904,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079904,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_buffer(struct buffer_head * bh)
```

```json
{
  "name": "unlock_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152608,
      "name": "unlock_buffer",
      "external": true,
      "loc": "fs/buffer.c:70",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152608,
      "name": "unlock_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
