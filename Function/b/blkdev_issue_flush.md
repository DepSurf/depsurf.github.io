# Function: <code>blkdev_issue_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767712,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:462",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767712,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583046080,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:463",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583046080,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151648,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:496",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151648,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583208208,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:504",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208208,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384592,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:521",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384592,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583594592,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:526",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583594592,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583701440,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:423",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701440,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890176,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:422",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890176,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993440,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993440,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584382432,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:439",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382432,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584496384,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:440",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584496384,
      "name": "blkdev_issue_flush",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device * bdev)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531040,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:438",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531040,
      "name": "blkdev_issue_flush",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device * bdev)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584941104,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:453",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/file.c:fat_file_fsync",
        "block/fops.c:blkdev_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941104,
      "name": "blkdev_issue_flush",
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
int blkdev_issue_flush(struct block_device * bdev)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585643584,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:459",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/file.c:fat_file_fsync",
        "block/fops.c:blkdev_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585643584,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int blkdev_issue_flush(struct block_device * bdev)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586415792,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:462",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/file.c:fat_file_fsync",
        "block/fops.c:blkdev_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586415792,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int blkdev_issue_flush(struct block_device * bdev)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663040,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:471",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/buffer.c:generic_buffers_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/file.c:fat_file_fsync",
        "block/fops.c:blkdev_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663040,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int blkdev_issue_flush(struct block_device * bdev)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586934272,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:469",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/buffer.c:generic_buffers_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/file.c:fat_file_fsync",
        "block/fops.c:blkdev_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934272,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495820240,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495820240,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229170424,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229170424,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290009232,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290009232,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274955084,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274955084,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583962176,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962176,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583899088,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899088,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945936,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945936,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int blkdev_issue_flush(struct block_device * bdev, gfp_t gfp_mask, sector_t * error_sector)
```

```json
{
  "name": "blkdev_issue_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584047920,
      "name": "blkdev_issue_flush",
      "external": true,
      "loc": "block/blk-flush.c:433",
      "file": "block/blk-flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/fat/file.c:fat_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584047920,
      "name": "blkdev_issue_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>sector_t * error_sector</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
