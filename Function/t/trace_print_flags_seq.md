# Function: <code>trace_print_flags_seq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235920,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:63",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_lazytime_template",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235920,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273136,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:63",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273136,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316352,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:63",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316352,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329488,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:64",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329488,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580383040,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:64",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383040,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580445024,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:64",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445024,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580500688,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500688,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557296,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557296,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580604880,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604880,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703376,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/iomap/trace.c:trace_raw_output_iomap_apply",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703376,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692672,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/iomap/trace.c:trace_raw_output_iomap_apply",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692672,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580696864,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/iomap/trace.c:trace_raw_output_iomap_apply",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696864,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873952,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/iomap/trace.c:trace_raw_output_iomap_iter",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873952,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581104592,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:66",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/locking/mutex.c:trace_raw_output_contention_begin",
        "kernel/module/main.c:trace_raw_output_module_load",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_throttled",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_write_folio",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:trace_raw_output_percpu_alloc_percpu",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/iomap/trace.c:trace_raw_output_iomap_iter",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104592,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413184,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/locking/mutex.c:trace_raw_output_contention_begin",
        "kernel/module/main.c:trace_raw_output_module_load",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_throttled",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_write_folio",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:trace_raw_output_percpu_alloc_percpu",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmalloc",
        "mm/slab_common.c:trace_raw_output_kmem_cache_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/iomap/trace.c:trace_raw_output_iomap_iter",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413184,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508304,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/locking/mutex.c:trace_raw_output_contention_begin",
        "kernel/module/main.c:trace_raw_output_module_load",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_throttled",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_write_folio",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:trace_raw_output_percpu_alloc_percpu",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmalloc",
        "mm/slab_common.c:trace_raw_output_kmem_cache_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/iomap/trace.c:trace_raw_output_iomap_dio_complete",
        "fs/iomap/trace.c:trace_raw_output_iomap_dio_rw_begin",
        "fs/iomap/trace.c:trace_raw_output_iomap_dio_rw_begin",
        "fs/iomap/trace.c:trace_raw_output_iomap_iter",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508304,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581619840,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/locking/mutex.c:trace_raw_output_contention_begin",
        "kernel/module/main.c:trace_raw_output_module_load",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_throttled",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_write_folio",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:trace_raw_output_percpu_alloc_percpu",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmalloc",
        "mm/slab_common.c:trace_raw_output_kmem_cache_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/iomap/trace.c:trace_raw_output_iomap_dio_complete",
        "fs/iomap/trace.c:trace_raw_output_iomap_dio_rw_begin",
        "fs/iomap/trace.c:trace_raw_output_iomap_dio_rw_begin",
        "fs/iomap/trace.c:trace_raw_output_iomap_iter",
        "fs/iomap/trace.c:trace_raw_output_iomap_class",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619840,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491904216,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491904216,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225846100,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225846100,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284992176,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284992176,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272191272,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272191272,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573680,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573680,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580520304,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520304,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580564928,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564928,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
const char * trace_print_flags_seq(struct trace_seq * p, const char * delim, long unsigned int flags, const struct trace_print_flags * flag_array)
```

```json
{
  "name": "trace_print_flags_seq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621648,
      "name": "trace_print_flags_seq",
      "external": true,
      "loc": "kernel/trace/trace_output.c:65",
      "file": "kernel/trace/trace_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:trace_raw_output_sched_switch",
        "kernel/time/timer.c:trace_raw_output_timer_start",
        "kernel/time/alarmtimer.c:trace_raw_output_alarm_class",
        "kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend",
        "kernel/module.c:trace_raw_output_module_load",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_writepage",
        "mm/vmscan.c:trace_raw_output_mm_shrink_slab_start",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd",
        "mm/slab_common.c:trace_raw_output_mm_page_alloc",
        "mm/slab_common.c:trace_raw_output_kmem_alloc_node",
        "mm/slab_common.c:trace_raw_output_kmem_alloc",
        "mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages",
        "fs/fs-writeback.c:trace_raw_output_writeback_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pte_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/dax.c:trace_raw_output_dax_pmd_fault_class",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_leases_conflict",
        "fs/locks.c:trace_raw_output_generic_add_lease",
        "fs/locks.c:trace_raw_output_filelock_lease",
        "fs/locks.c:trace_raw_output_filelock_lock",
        "fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__es_extent",
        "fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit",
        "fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter",
        "fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode",
        "fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc",
        "fs/ext4/super.c:trace_raw_output_ext4_free_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_request_blocks",
        "fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent",
        "drivers/ras/ras.c:trace_raw_output_aer_event",
        "drivers/ras/ras.c:trace_raw_output_aer_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621648,
      "name": "trace_print_flags_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
