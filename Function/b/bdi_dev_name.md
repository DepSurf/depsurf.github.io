# Function: <code>bdi_dev_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582076710,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const char * bdi_dev_name(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581426960,
      "name": "bdi_dev_name",
      "external": true,
      "loc": "mm/backing-dev.c:1036",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:__blkg_prfill_u64",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426960,
      "name": "bdi_dev_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
const char * bdi_dev_name(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470240,
      "name": "bdi_dev_name",
      "external": true,
      "loc": "mm/backing-dev.c:905",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:__blkg_prfill_u64",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470240,
      "name": "bdi_dev_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
const char * bdi_dev_name(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491024,
      "name": "bdi_dev_name",
      "external": true,
      "loc": "mm/backing-dev.c:904",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:__blkg_prfill_u64",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491024,
      "name": "bdi_dev_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
const char * bdi_dev_name(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749664,
      "name": "bdi_dev_name",
      "external": true,
      "loc": "mm/backing-dev.c:987",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "block/blk-cgroup.c:blkcg_print_one_stat",
        "block/blk-cgroup.c:__blkg_prfill_u64",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749664,
      "name": "bdi_dev_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
const char * bdi_dev_name(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132032,
      "name": "bdi_dev_name",
      "external": true,
      "loc": "mm/backing-dev.c:993",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:__blkg_prfill_u64",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132032,
      "name": "bdi_dev_name",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
const char * bdi_dev_name(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582607808,
      "name": "bdi_dev_name",
      "external": true,
      "loc": "mm/backing-dev.c:1116",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:__blkg_prfill_u64",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607808,
      "name": "bdi_dev_name",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
const char * bdi_dev_name(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816512,
      "name": "bdi_dev_name",
      "external": true,
      "loc": "mm/backing-dev.c:1129",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:__blkg_prfill_u64",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816512,
      "name": "bdi_dev_name",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const char * bdi_dev_name(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990992,
      "name": "bdi_dev_name",
      "external": true,
      "loc": "mm/backing-dev.c:1125",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:__blkg_prfill_u64",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_timer",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990992,
      "name": "bdi_dev_name",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493609132,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227153580,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287196724,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273256514,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582045446,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581982998,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582036726,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
  "name": "bdi_dev_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582108342,
      "name": "bdi_dev_name",
      "external": false,
      "loc": "include/linux/backing-dev.h:510",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
const char * bdi_dev_name(struct backing_dev_info * bdi)
```
</details>
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
