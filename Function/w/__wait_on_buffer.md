# Function: <code>__wait_on_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581219440,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:121",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:unmap_underlying_metadata",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__block_write_begin",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219440,
      "name": "__wait_on_buffer",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395738,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:122",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:unmap_underlying_metadata",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383744,
      "name": "__wait_on_buffer",
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581474097,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:123",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461888,
      "name": "__wait_on_buffer",
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581529226,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:123",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517136,
      "name": "__wait_on_buffer",
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581671615,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:123",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659488,
      "name": "__wait_on_buffer",
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581835307,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:116",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821472,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581922585,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:116",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909088,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582059874,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045872,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582137673,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123584,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582374058,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:120",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:osync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357568,
      "name": "__wait_on_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582430362,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:120",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:osync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415088,
      "name": "__wait_on_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457146,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:120",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442384,
      "name": "__wait_on_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582780762,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:120",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764688,
      "name": "__wait_on_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583320064,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:120",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:bh_submit_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314128,
      "name": "__wait_on_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583903889,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:120",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900704,
      "name": "__wait_on_buffer",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584128177,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:120",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/mmp.c:write_mmp_block_thawed",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124656,
      "name": "__wait_on_buffer",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584344801,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:121",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/mmp.c:write_mmp_block_thawed",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340864,
      "name": "__wait_on_buffer",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493682912,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493660800,
      "name": "__wait_on_buffer",
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227215332,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227198112,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287291248,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287265840,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273306204,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273292862,
      "name": "__wait_on_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582106409,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092320,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582043849,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029840,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582096889,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082800,
      "name": "__wait_on_buffer",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "__wait_on_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582169814,
      "name": "__wait_on_buffer",
      "external": true,
      "loc": "fs/buffer.c:117",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/misc.c:fat_sync_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156448,
      "name": "__wait_on_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
