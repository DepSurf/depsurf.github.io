# Function: <code>blk_get_backing_dev_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info * blk_get_backing_dev_info(struct block_device * bdev)
```

```json
{
  "name": "blk_get_backing_dev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582729632,
      "name": "blk_get_backing_dev_info",
      "external": true,
      "loc": "block/blk-core.c:114",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582729632,
      "name": "blk_get_backing_dev_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct backing_dev_info * blk_get_backing_dev_info(struct block_device * bdev)
```

```json
{
  "name": "blk_get_backing_dev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583007376,
      "name": "blk_get_backing_dev_info",
      "external": true,
      "loc": "block/blk-core.c:114",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007376,
      "name": "blk_get_backing_dev_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct backing_dev_info * blk_get_backing_dev_info(struct block_device * bdev)
```

```json
{
  "name": "blk_get_backing_dev_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112368,
      "name": "blk_get_backing_dev_info",
      "external": true,
      "loc": "block/blk-core.c:115",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112368,
      "name": "blk_get_backing_dev_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct backing_dev_info * blk_get_backing_dev_info(struct block_device * bdev)
```
</details>
</li>
</ul>
