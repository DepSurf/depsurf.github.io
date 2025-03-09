# Function: <code>wait_on_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581221454,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:unmap_underlying_metadata",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__block_write_begin",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529267,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581546562,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557871,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613794,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582133203,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825403,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581903823,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906387,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912929,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929367,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984359,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:340",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581395631,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:unmap_underlying_metadata",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714883,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581732357,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743720,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806267,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915261,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021343,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090590,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582093365,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582099897,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115672,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125617,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197348,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:344",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581473990,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802515,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581819957,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831448,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581895691,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582003535,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111439,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582180692,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582183461,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189989,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205912,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215393,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286852,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:347",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581529178,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581873796,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581943543,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988833,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582073758,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090600,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223230,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582267011,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582269614,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275852,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291424,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582300842,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582371348,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:348",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581671566,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023796,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582093121,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138257,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223198,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582240277,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582372248,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582416077,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418766,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582425017,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440496,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449922,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582522132,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581835237,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582211939,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582281188,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320997,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412958,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429993,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542526,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582606694,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582609384,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582615373,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630911,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640360,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713520,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581922515,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306787,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582379924,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424565,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512414,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582529513,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643646,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582708435,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582711128,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582717117,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732735,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742118,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817552,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582059811,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582473165,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582548438,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593607,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582681501,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699412,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582814870,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881789,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884531,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582890680,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906467,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582916105,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992528,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582137603,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582572093,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582649243,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694534,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783661,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582801613,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918212,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988269,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991107,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997256,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013155,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583022649,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098720,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582374016,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:osync_buffers_list",
        "fs/buffer.c:osync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880573,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582961273,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583006671,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095818,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114014,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583229694,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304468,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583307773,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313579,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583330824,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583417680,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582430320,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:osync_buffers_list",
        "fs/buffer.c:osync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953421,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583079603,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175142,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193022,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321682,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583419721,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583422957,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583428653,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446888,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583532112,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582457104,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582979349,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583104631,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201686,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220685,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583344498,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583442775,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445757,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451307,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583467702,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583555264,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582780720,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583315221,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583444782,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544929,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583564430,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687235,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583792205,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583795261,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583801100,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818598,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583913568,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:352",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583320009,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:bh_submit_read",
        "fs/buffer.c:bh_submit_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583822661,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583967667,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078617,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584100825,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584240952,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584356094,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584359311,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584365715,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584389737,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584491327,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:374",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wait_on_buffer(struct buffer_head * bh)
```

```json
{
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583903865,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445061,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595454,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584711428,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584734489,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584885649,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585006404,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009683,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585016835,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    },
    {
      "addr": 18446744071585045683,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585157405,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:381",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585014816,
      "name": "wait_on_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584128153,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584674053,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821758,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935287,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block_thawed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584957821,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585112817,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585233904,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585237251,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585244445,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585274522,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386541,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:394",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584344777,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584906773,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585054719,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585166855,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block_thawed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585188909,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585345265,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_read_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585467106,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585470594,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477719,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585505219,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_fc_wait_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585621405,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:385",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493682872,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494219060,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494301668,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494351636,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494452864,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494471588,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494594556,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494672248,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494676988,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494683392,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494702636,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494717412,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494805892,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227215220,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3227649860,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227736112,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227785556,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 3227888120,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 3227907332,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3228037332,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 3228112976,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 3228116652,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 3228123504,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 3228138120,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 3228152640,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3228225212,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287291124,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287915128,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288018444,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288081324,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288205784,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288230016,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288395884,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288486380,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288490700,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288498952,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288523796,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288538140,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288645140,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273306088,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273675802,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273743176,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273781308,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273861634,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273876564,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273972328,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274032356,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274035342,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274041340,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274056314,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274066302,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274133900,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582106339,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582540829,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582617979,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663270,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582752397,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770349,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582886948,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957005,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582959843,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582965992,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981891,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991385,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067456,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582043779,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582477997,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582555147,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582600438,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689565,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582707517,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582824100,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582894157,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896995,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582903144,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919043,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582928537,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583004608,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582096819,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582531309,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582607835,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582653126,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742253,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759597,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875844,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582945613,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948451,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954600,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970499,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582979993,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583056064,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
  "name": "wait_on_buffer",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582169744,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612061,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582690449,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738168,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582827512,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582845508,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962532,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583033911,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036851,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:jread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043106,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059026,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069093,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583145262,
      "name": "wait_on_buffer",
      "external": false,
      "loc": "include/linux/buffer_head.h:350",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_sync_bhs"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void wait_on_buffer(struct buffer_head * bh)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void wait_on_buffer(struct buffer_head * bh)
```
</details>
</li>
</ul>
