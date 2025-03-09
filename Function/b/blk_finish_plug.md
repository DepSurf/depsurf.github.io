# Function: <code>blk_finish_plug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582759760,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:3318",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:generic_writepages",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/vmscan.c:shrink_lruvec",
        "mm/madvise.c:SyS_madvise",
        "mm/swap_state.c:swapin_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:do_io_submit",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759760,
      "name": "blk_finish_plug",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583037792,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:3290",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:generic_writepages",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:SyS_madvise",
        "mm/swap_state.c:swapin_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:do_io_submit",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037792,
      "name": "blk_finish_plug",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583142816,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:3290",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:generic_writepages",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:SyS_madvise",
        "mm/swap_state.c:swapin_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:do_io_submit",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583142816,
      "name": "blk_finish_plug",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583199952,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:3395",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:SyS_madvise",
        "mm/swap_state.c:swapin_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:do_io_submit",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583199952,
      "name": "blk_finish_plug",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583376272,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:3619",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:SyS_madvise",
        "mm/swap_state.c:do_swap_page_readahead",
        "mm/swap_state.c:swapin_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:do_io_submit",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376272,
      "name": "blk_finish_plug",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583585744,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:3748",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585744,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583694464,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1790",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694464,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583882960,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1741",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__do_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882960,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583986160,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__do_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986160,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584375136,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1873",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_lruvec",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375136,
      "name": "blk_finish_plug",
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584489360,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1768",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image",
        "kernel/power/swap.c:save_image",
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_lruvec",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489360,
      "name": "blk_finish_plug",
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584524016,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1760",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image",
        "kernel/power/swap.c:save_image",
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_lruvec",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524016,
      "name": "blk_finish_plug",
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584934896,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1746",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image",
        "kernel/power/swap.c:save_image",
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_lruvec",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x64_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/fops.c:blkdev_write_iter",
        "block/fops.c:__blkdev_direct_IO",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584934896,
      "name": "blk_finish_plug",
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585636560,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1227",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image",
        "kernel/power/swap.c:save_image",
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_lruvec",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:do_madvise",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/fops.c:blkdev_write_iter",
        "block/fops.c:__blkdev_direct_IO",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "io_uring/io_uring.c:io_submit_sqes",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585636560,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586407808,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1165",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image",
        "kernel/power/swap.c:save_image",
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:lru_gen_seq_write",
        "mm/vmscan.c:lru_gen_shrink_lruvec",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:do_madvise",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/fops.c:blkdev_write_iter",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "io_uring/io_uring.c:io_submit_sqes",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586407808,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586655120,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1162",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image",
        "kernel/power/swap.c:save_image",
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:lru_gen_seq_write",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:do_madvise",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/mpage.c:mpage_writepages",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "io_uring/io_uring.c:io_submit_sqes",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586655120,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586926384,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1197",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image",
        "kernel/power/swap.c:save_image",
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:lru_gen_seq_write",
        "mm/vmscan.c:lru_gen_shrink_node",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:do_madvise",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/mpage.c:mpage_writepages",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/fops.c:blkdev_writepages",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "io_uring/io_uring.c:io_submit_sqes",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926384,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495811552,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__arm64_compat_sys_io_submit",
        "fs/aio.c:__arm64_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495811552,
      "name": "blk_finish_plug",
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229162992,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__se_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:fsync_buffers_list",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__se_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229162992,
      "name": "blk_finish_plug",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289998304,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__se_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__se_compat_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289998304,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274948672,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__se_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__se_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274948672,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583954896,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__do_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954896,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583891824,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__do_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891824,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583938656,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__do_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938656,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_finish_plug(struct blk_plug * plug)
```

```json
{
  "name": "blk_finish_plug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584040656,
      "name": "blk_finish_plug",
      "external": true,
      "loc": "block/blk-core.c:1782",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/madvise.c:__do_sys_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "fs/fs-writeback.c:wb_writeback",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/io_uring.c:io_submit_state_end",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__flush_batch",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/dm-kcopyd.c:do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584040656,
      "name": "blk_finish_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
