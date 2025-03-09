# Function: <code>inode_to_bdi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580475586,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__generic_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519268,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532086,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:force_page_cache_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551663,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580703997,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580750436,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580883179,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930889,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952585,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581167264,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "fs/fs-writeback.c:sync_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695887,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085079,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:175",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580559334,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605545,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580620015,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642799,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580818206,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580869636,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:SyS_fadvise64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011777,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077257,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101760,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352229,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887631,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313547,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580624422,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580672692,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580686310,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580709871,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580883725,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580937556,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:SyS_fadvise64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963617,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085974,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152857,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176967,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431141,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581976639,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401881,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:176",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580652182,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710341,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719750,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580744731,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580928020,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580981541,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:SyS_fadvise64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010347,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133625,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200159,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224269,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581485311,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192783,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582485828,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:151",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580743446,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790900,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580805446,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831892,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581027696,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581084216,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:SyS_fadvise64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105833,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248645,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330094,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355069,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581627455,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582341455,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637028,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:153",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580878953,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927268,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942508,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968916,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581162477,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222725,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259902,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395644,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478248,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581503928,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581786111,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582530847,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582830570,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580946521,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966995,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:vfs_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003284,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018492,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045654,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581242362,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342920,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476738,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560584,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589768,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581872895,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631935,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582933874,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:154",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581043811,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062097,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:vfs_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066693,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082488,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109126,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581316879,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453340,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591418,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674382,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581700794,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581995233,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582804575,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113928,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581099283,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117821,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122661,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581138472,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166118,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581375983,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517550,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655065,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746758,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774250,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582070721,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582907935,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583219720,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581275315,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301565,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310293,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323288,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359316,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574690,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725100,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879141,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967674,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581995733,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582306433,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947948,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_buffered_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221471,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546742,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:155",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581322387,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581344733,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357676,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581365112,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402749,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620226,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581922641,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016614,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044991,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582359425,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583021956,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_buffered_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323390,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583656923,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581341971,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363821,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376873,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384645,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420573,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642648,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581950610,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042447,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070993,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582387185,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047284,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_buffered_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583346208,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677642,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_add",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581573651,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612205,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625852,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633701,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671107,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910632,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582255224,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350159,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582385648,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_user_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582708321,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583385060,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_buffered_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690032,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584036545,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:136",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct backing_dev_info * inode_to_bdi(struct inode * inode)
```

```json
{
  "name": "inode_to_bdi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582135216,
      "name": "inode_to_bdi",
      "external": true,
      "loc": "mm/backing-dev.c:977",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/page-writeback.c:folio_account_redirty",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:hwpoison_user_mappings",
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
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135216,
      "name": "inode_to_bdi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct backing_dev_info * inode_to_bdi(struct inode * inode)
```

```json
{
  "name": "inode_to_bdi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582612464,
      "name": "inode_to_bdi",
      "external": true,
      "loc": "mm/backing-dev.c:1100",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/page-writeback.c:folio_account_redirty",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:hwpoison_user_mappings",
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
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582612464,
      "name": "inode_to_bdi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct backing_dev_info * inode_to_bdi(struct inode * inode)
```

```json
{
  "name": "inode_to_bdi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582821248,
      "name": "inode_to_bdi",
      "external": true,
      "loc": "mm/backing-dev.c:1113",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/page-writeback.c:folio_account_redirty",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_needs_dirty_tracking",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:hwpoison_user_mappings",
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
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582821248,
      "name": "inode_to_bdi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct backing_dev_info * inode_to_bdi(struct inode * inode)
```

```json
{
  "name": "inode_to_bdi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582995952,
      "name": "inode_to_bdi",
      "external": true,
      "loc": "mm/backing-dev.c:1109",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/fadvise.c:generic_fadvise",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/page-writeback.c:folio_redirty_for_writepage",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "mm/readahead.c:file_ra_state_init",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_needs_dirty_tracking",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:hwpoison_user_mappings",
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
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995952,
      "name": "inode_to_bdi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492464188,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492486620,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492494328,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492512996,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492549960,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492781956,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492940808,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493105040,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493200052,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493231448,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493601424,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494583424,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494939868,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226340000,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226359768,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 3226365368,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 3226382696,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226422572,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3226598592,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226726608,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 3226800548,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 3226831304,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227149460,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 3228026044,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 3228350164,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285744884,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285772744,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285781268,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285802060,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285852112,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286150496,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286352788,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286568228,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286703888,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286749124,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287191188,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288381268,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288813316,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272535214,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272550924,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272554960,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272570310,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272593178,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272754296,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272857904,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272952450,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272979014,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273250280,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273962928,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274245434,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581068131,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086669,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091509,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107320,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134966,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581344831,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486286,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623801,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715494,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581742986,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582039457,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876671,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583188456,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581015331,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033853,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038693,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581054392,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081910,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581288543,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428542,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565091,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654394,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681610,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581977025,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813823,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125608,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581059331,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077869,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082709,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581098520,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126166,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581336031,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581477598,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615113,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706806,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734298,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582030737,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865551,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172488,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
  "name": "inode_to_bdi",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581120915,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139757,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581145653,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160730,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:force_page_cache_readahead",
        "mm/readahead.c:file_ra_state_init",
        "mm/readahead.c:file_ra_state_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188678,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581399983,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_wants_writenotify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542339,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678455,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774198,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802586,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582104497,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:write_inode_now",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582952207,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266166,
      "name": "inode_to_bdi",
      "external": false,
      "loc": "include/linux/backing-dev.h:159",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct backing_dev_info * inode_to_bdi(struct inode * inode)
```
</details>
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
