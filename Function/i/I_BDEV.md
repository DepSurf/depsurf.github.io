# Function: <code>I_BDEV</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581233328,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:47",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_block",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:iterate_bdevs"
      ],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapon",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:memory_failure",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:sync_inode",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233328,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581409776,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:48",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_writepages",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:memory_failure",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399472,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581482821,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:50",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_writepages",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:memory_failure",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477808,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545252,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_writepages",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533584,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581688100,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_writepages",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676112,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581851235,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839216,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581938771,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:vfs_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926464,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582076618,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:vfs_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064096,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582154090,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141760,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582390970,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/vmscan.c:pageout",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378224,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582444890,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:bdev_alloc",
        "fs/block_dev.c:bdev_free_inode",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/vmscan.c:pageout",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/io_uring.c:io_file_supports_async",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/ioctl.c:compat_blkdev_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_validate_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433760,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582471882,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:bdev_alloc",
        "fs/block_dev.c:bdev_free_inode",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/vmscan.c:pageout",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/io_uring.c:__io_file_supports_async",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/ioctl.c:compat_blkdev_ioctl",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:loop_validate_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460688,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584895276,
      "name": "I_BDEV",
      "external": true,
      "loc": "block/bdev.c:42",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:iterate_bdevs",
        "block/bdev.c:bdev_alloc",
        "block/bdev.c:bdev_free_inode"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/vmscan.c:pageout",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/io_uring.c:__io_file_supports_nowait",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_write_iter",
        "block/fops.c:block_ioctl",
        "block/fops.c:blkdev_close",
        "block/fops.c:blkdev_fsync",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_iopoll",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/fops.c:blkdev_get_block",
        "block/ioctl.c:compat_blkdev_ioctl",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:loop_validate_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584889344,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585592443,
      "name": "I_BDEV",
      "external": true,
      "loc": "block/bdev.c:42",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_alloc"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapoff",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "io_uring/io_uring.c:io_file_get_flags",
        "drivers/block/loop.c:loop_validate_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585587984,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586359307,
      "name": "I_BDEV",
      "external": true,
      "loc": "block/bdev.c:43",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_alloc"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapoff",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_get_block",
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_common_ioctl",
        "io_uring/io_uring.c:io_file_get_flags",
        "drivers/block/loop.c:loop_validate_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586354368,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586605474,
      "name": "I_BDEV",
      "external": true,
      "loc": "block/bdev.c:43",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_alloc"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapoff",
        "block/fops.c:blkdev_mmap",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_write_iter",
        "block/fops.c:blkdev_release",
        "block/fops.c:blkdev_fsync",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/fops.c:blkdev_get_block",
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_validate_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600992,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586874818,
      "name": "I_BDEV",
      "external": true,
      "loc": "block/bdev.c:46",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_alloc"
      ],
      "caller_func": [
        "block/fops.c:blkdev_mmap",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_read_iter",
        "block/fops.c:blkdev_write_iter",
        "block/fops.c:blkdev_fsync",
        "block/fops.c:blkdev_get_block",
        "block/fops.c:blkdev_iomap_begin",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/ioctl.c:compat_blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "drivers/block/loop.c:loop_validate_file",
        "drivers/block/loop.c:__loop_update_dio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586870304,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493706556,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493691440,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227233968,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/vmscan.c:shrink_page_list",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227219564,
      "name": "I_BDEV",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287311404,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287291728,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273322396,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273309876,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582122826,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110496,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582060266,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047936,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582113306,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100976,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct block_device * I_BDEV(struct inode * inode)
```

```json
{
  "name": "I_BDEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582186262,
      "name": "I_BDEV",
      "external": true,
      "loc": "fs/block_dev.c:51",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:block_ioctl",
        "fs/block_dev.c:blkdev_close",
        "fs/block_dev.c:blkdev_fsync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/buffer.c:init_page_buffers",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173840,
      "name": "I_BDEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
