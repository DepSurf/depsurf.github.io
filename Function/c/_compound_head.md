# Function: <code>_compound_head</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_compound_head",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592036570,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578864910,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305492,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309960,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579616585,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579625413,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580112035,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580407446,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580743718,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445127,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536841,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561131,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581568181,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:try_to_release_page",
        "mm/filemap.c:try_to_release_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_async",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:wait_on_page_private_2_killable",
        "mm/filemap.c:wait_on_page_private_2",
        "mm/filemap.c:end_page_private_2",
        "mm/filemap.c:end_page_private_2",
        "mm/filemap.c:unlock_page",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:add_to_page_cache_lru",
        "mm/filemap.c:add_to_page_cache_lru",
        "mm/filemap.c:add_to_page_cache_lru",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:filemap_range_needs_writeback",
        "mm/filemap.c:filemap_range_needs_writeback",
        "mm/filemap.c:filemap_range_needs_writeback",
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615925,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:wait_on_page_writeback_killable",
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632313,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "mm/readahead.c:read_cache_pages_invalidate_page",
        "mm/readahead.c:read_cache_pages_invalidate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638229,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_cache_add_inactive_or_unevictable",
        "mm/swap.c:lru_cache_add",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:lru_note_cost_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:get_kernel_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652402,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672960,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:perf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720669,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730879,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__page_mapcount",
        "mm/util.c:__page_mapcount",
        "mm/util.c:page_mapping",
        "mm/util.c:page_mapping",
        "mm/util.c:page_mapping",
        "mm/util.c:page_mapping",
        "mm/util.c:page_anon_vma",
        "mm/util.c:page_rmapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780451,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_dump_obj",
        "mm/slab_common.c:kmem_dump_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800662,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:pageblock_skip_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821909,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823083,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838406,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:put_compound_head",
        "mm/gup.c:put_compound_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872421,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:numa_migrate_prep",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:validate_page_before_insert",
        "mm/memory.c:validate_page_before_insert",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581893236,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581896580,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:__munlock_isolation_failed",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902304,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927514,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944824,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965706,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/rmap.c:hugepage_add_anon_rmap",
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:page_mlock",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:page_move_anon_rmap",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582032049,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:free_contig_range",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:move_freepages_block",
        "mm/page_alloc.c:prep_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592788194,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051003,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055433,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:swap_slot_free_notify",
        "mm/page_io.c:swap_slot_free_notify",
        "mm/page_io.c:swap_slot_free_notify",
        "mm/page_io.c:end_swap_bio_write",
        "mm/page_io.c:end_swap_bio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582061004,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085525,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:page_trans_huge_map_swapcount",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091736,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582098584,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144950,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:gather_bootmem_prealloc",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:hugetlb_basepage_index",
        "mm/hugetlb.c:hugetlb_basepage_index",
        "mm/hugetlb.c:hugetlb_basepage_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582160784,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:lookup_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196389,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_migrate_page",
        "mm/ksm.c:rmap_walk_ksm",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582213272,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:__ksize",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:check_slab",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615401483,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_init_pool",
        "mm/kfence/core.c:kfence_init_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582249475,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:migrate_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582297088,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:free_transhuge_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:can_split_huge_page",
        "mm/huge_memory.c:can_split_huge_page",
        "mm/huge_memory.c:can_split_huge_page",
        "mm/huge_memory.c:can_split_huge_page",
        "mm/huge_memory.c:page_trans_huge_mapcount",
        "mm/huge_memory.c:page_trans_huge_mapcount",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:is_transparent_hugepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318958,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:release_pte_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354883,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:unlock_page_memcg",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:__mod_lruvec_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582388582,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:identify_page_state",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392482,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582403386,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "mm/zsmalloc.c:trylock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409267,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410661,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417851,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420515,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page",
        "mm/page_idle.c:page_idle_get_page",
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421116,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582422945,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582430690,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_wait_for_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494613,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505864,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:generic_pipe_buf_get",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582516901,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675582,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582704044,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722885,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760462,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582775682,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:create_page_buffers",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:init_page_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:__find_get_block_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792611,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_zero_block",
        "fs/direct-io.c:dio_zero_block",
        "fs/direct-io.c:dio_zero_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798454,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881366,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582905311,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_buffer_account_pin",
        "fs/io_uring.c:io_buffer_account_pin",
        "fs/io_uring.c:io_buffer_account_pin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007309,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028536,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/crypto/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583033285,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:read_file_data_page",
        "fs/verity/enable.c:read_file_data_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040209,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583042900,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583106508,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120634,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_releasepage",
        "fs/iomap/buffered-io.c:iomap_releasepage",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/iomap/buffered-io.c:iomap_page_create",
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126366,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172868,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583257612,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583263947,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583428812,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583482042,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_set_page_dirty",
        "fs/ext4/inode.c:ext4_set_page_dirty",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583513642,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583548184,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587712,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583590445,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583724421,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583772265,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583786020,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583787190,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page",
        "fs/jbd2/commit.c:release_buffer_page",
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583841609,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592276395,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851009,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583866989,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_huge_page",
        "fs/hugetlbfs/inode.c:remove_huge_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583938941,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_readpage",
        "fs/ecryptfs/mmap.c:ecryptfs_writepage",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939701,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583990078,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584016973,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584058874,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584316271,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584502189,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584895843,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911035,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584953141,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585033462,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/core.c:read_part_sector",
        "block/partitions/core.c:read_part_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585033862,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585036243,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585037470,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585041606,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585049320,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585053605,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585055564,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585056189,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585056881,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585057567,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585058456,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585062323,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585062891,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585226069,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:pipe_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518025,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586073006,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765294,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586773361,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/grant-table.c:gnttab_end_foreign_access",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200984,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225164,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935736,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587952958,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588071524,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588192711,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pio_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588344130,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588400450,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589280060,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589335028,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589805384,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589835399,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589887395,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:skb_add_rx_frag",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589901937,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589953400,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590151680,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590197368,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590220677,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_skb_page",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590404945,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590696305,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590773755,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp.c:tcp_build_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590835831,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591199413,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591259083,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591311548,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591364823,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591767054,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591900297,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591945805,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:194",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_clean_una"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int _compound_head(const struct page * page)
```

```json
{
  "name": "_compound_head",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593802349,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578860981,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360110,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367417,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579709661,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579720970,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580252576,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580624655,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957366,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785066,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886445,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912983,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581932296,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:filemap_range_has_writeback",
        "mm/filemap.c:filemap_range_has_writeback",
        "mm/filemap.c:filemap_range_has_writeback",
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581976036,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581995941,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/folio-compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:try_to_release_page",
        "mm/folio-compat.c:delete_from_page_cache",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:lru_cache_add",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_writeback",
        "mm/folio-compat.c:migrate_page_copy",
        "mm/folio-compat.c:migrate_page_copy",
        "mm/folio-compat.c:migrate_page_states",
        "mm/folio-compat.c:migrate_page_states",
        "mm/folio-compat.c:migrate_page_move_mapping",
        "mm/folio-compat.c:migrate_page_move_mapping",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:page_mapped",
        "mm/folio-compat.c:wait_for_stable_page",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:end_page_writeback",
        "mm/folio-compat.c:unlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997456,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582019185,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__activate_page",
        "mm/swap.c:pagevec_move_tail_fn",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:get_kernel_pages",
        "mm/swap.c:__put_page",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023718,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582053269,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095663,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111680,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__page_mapcount",
        "mm/util.c:__page_mapcount",
        "mm/util.c:page_rmapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582170361,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_dump_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582194725,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214341,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582232750,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_get_folio",
        "mm/gup.c:try_get_folio"
      ],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ]
    },
    {
      "addr": 18446744071582286060,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:numa_migrate_prep",
        "mm/memory.c:insert_pages",
        "mm/memory.c:insert_pages",
        "mm/memory.c:insert_pages",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:restore_exclusive_pte"
      ]
    },
    {
      "addr": 18446744071582291428,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303999,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:munlock_page",
        "mm/mlock.c:mlock_new_page",
        "mm/mlock.c:mlock_new_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306495,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333904,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350859,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582384285,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/rmap.c:hugepage_add_anon_rmap",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_move_anon_rmap",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411727,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582460202,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:free_contig_range",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:move_freepages_block",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594687185,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582474191,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_inject_error",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491734,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "mm/page_io.c:end_swap_bio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582499112,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582525651,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:try_to_free_swap",
        "mm/swapfile.c:try_to_free_swap",
        "mm/swapfile.c:try_to_free_swap",
        "mm/swapfile.c:try_to_free_swap",
        "mm/swapfile.c:try_to_free_swap",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582538082,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598672,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:hugetlb_basepage_index",
        "mm/hugetlb.c:hugetlb_basepage_index",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582616181,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594710231,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658715,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678272,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582707554,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_init_pool",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "mm/kfence/core.c:kfence_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582735835,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:move_to_new_folio",
        "mm/migrate.c:writeout",
        "mm/migrate.c:writeout",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_page",
        "mm/migrate.c:migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737243,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784912,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:free_transhuge_page",
        "mm/huge_memory.c:free_transhuge_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071582810922,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:release_pte_page"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071582866117,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:unlock_page_memcg",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:mem_cgroup_css_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897150,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:add_to_kill",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": [
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    },
    {
      "addr": 18446744071582903087,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582915994,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582921242,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923470,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931517,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934909,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "mm/page_idle.c:page_idle_get_page",
        "mm/page_idle.c:page_idle_get_page",
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936191,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:check_heap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582940160,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page",
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582946929,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019618,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032288,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:generic_pipe_buf_get",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583041173,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221637,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267766,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328363,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:create_page_buffers",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:init_page_buffers",
        "fs/buffer.c:alloc_page_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:__find_get_block_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583344497,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583351303,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446810,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583477553,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583501641,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/crypto/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507167,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583514723,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583518202,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583588540,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583605893,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_migrate_page",
        "fs/iomap/buffered-io.c:iomap_migrate_page",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615543,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583667822,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757999,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583765810,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583947281,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006308,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044048,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082568,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125752,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129319,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335308,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584351010,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410288,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594058293,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420286,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439680,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_huge_page",
        "fs/hugetlbfs/inode.c:remove_huge_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519518,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_read_folio",
        "fs/ecryptfs/mmap.c:ecryptfs_writepage",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ]
    },
    {
      "addr": 18446744071584520428,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584575765,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584608632,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650314,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935951,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585139134,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596514,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585611649,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:__bio_release_pages",
        "block/bio.c:__bio_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585656979,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585750654,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/core.c:read_part_sector",
        "block/partitions/core.c:read_part_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585751249,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754119,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585755724,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585760346,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585769010,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774483,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777018,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777919,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778676,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585779643,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585780675,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585784738,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785589,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585976885,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_buffer_account_pin",
        "io_uring/io_uring.c:io_buffer_account_pin",
        "io_uring/io_uring.c:io_buffer_account_pin"
      ],
      "caller_func": [
        "io_uring/io_uring.c:virt_to_head_page"
      ]
    },
    {
      "addr": 18446744071586064753,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:pipe_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:pipe_get_pages",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:page_copy_sane"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586670128,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587296103,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045218,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588052706,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588505068,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588535915,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589289282,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589436491,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589574870,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589739068,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589800887,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590761931,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590807356,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591327720,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591350834,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591416270,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:skb_add_rx_frag",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591431327,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591709514,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591760270,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591770438,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0",
        "net/core/gro.c:skb_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591798181,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_skb_page",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592001790,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592324427,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592406277,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag",
        "net/ipv4/tcp.c:tcp_build_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592471866,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592860496,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592925090,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592981264,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593037734,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593486401,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593615347,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593667503,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:270",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215152,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071582239776,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071593988992,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582747280,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071582787536,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071582878144,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584516720,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585947072,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int _compound_head(const struct page * page)
```

```json
{
  "name": "_compound_head",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627481880,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578863749,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579431164,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441381,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579835403,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579848634,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580453004,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580890543,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252550,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224755,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319313,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348055,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582370757,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410996,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582431813,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/folio-compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:lru_cache_add_inactive_or_unevictable",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_writeback",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:wait_for_stable_page",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:end_page_writeback",
        "mm/folio-compat.c:unlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433670,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582446887,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457814,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582510042,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:get_pfn_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582567611,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582587285,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:page_rmapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655458,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__ksize",
        "mm/slab_common.c:kfree",
        "mm/slab_common.c:kmem_dump_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678912,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:pageblock_skip_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582702421,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582723337,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778765,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:insert_pages",
        "mm/memory.c:insert_pages",
        "mm/memory.c:insert_pages"
      ],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:numa_migrate_prep",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ]
    },
    {
      "addr": 18446744071582798487,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:munlock_page",
        "mm/mlock.c:mlock_new_page",
        "mm/mlock.c:mlock_new_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582801244,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834854,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:can_change_pte_writable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582855837,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_mapped_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887944,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/rmap.c:hugepage_add_anon_rmap",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_move_anon_rmap",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919004,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582974106,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:free_contig_range",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:move_freepages_block",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596423615,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988357,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_inject_error",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583006454,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_fs",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "mm/page_io.c:end_swap_bio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013064,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:free_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583025279,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053471,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117207,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_fresh_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_basepage_index",
        "mm/hugetlb.c:hugetlb_basepage_index",
        "mm/hugetlb.c:PageHuge",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:__update_and_free_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    },
    {
      "addr": 18446744071583140105,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596455033,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182107,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220718,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free",
        "mm/slub.c:cache_from_obj",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583233215,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_init_pool",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "mm/kfence/core.c:kfence_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260428,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278121,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317872,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:free_transhuge_page",
        "mm/huge_memory.c:free_transhuge_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:can_change_pmd_writable",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071583345384,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:set_huge_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:alloc_charge_hpage",
        "mm/khugepaged.c:alloc_charge_hpage",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:release_pte_page"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071583401994,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:mem_cgroup_from_slab_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:unlock_page_memcg",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:mem_cgroup_css_from_page"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    },
    {
      "addr": 18446744071583424005,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583449373,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:__free_raw_hwp_pages",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/memory-failure.c:truncate_error_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:add_to_kill",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": [
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    },
    {
      "addr": 18446744071583455215,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583470461,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583476630,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583478955,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487462,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583490685,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "mm/page_idle.c:page_idle_get_page",
        "mm/page_idle.c:page_idle_get_page",
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492185,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:check_heap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496278,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init",
        "mm/memremap.c:free_zone_device_page",
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583503943,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585059,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583596640,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:generic_pipe_buf_get",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606885,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583801333,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583850164,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914368,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:create_page_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:init_page_buffers",
        "fs/buffer.c:alloc_page_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:__find_get_block_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583927923,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583934010,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:clean_page_buffers",
        "fs/mpage.c:clean_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584032778,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_free_ring",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584071841,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103885,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584113335,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584114521,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192779,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584210533,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218951,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584274668,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584374709,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584383256,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:kpagecount_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584574038,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636430,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584681520,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584715480,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584759573,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584762956,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584984357,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585001122,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585066453,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585078070,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080094,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585100920,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585190206,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_read_folio",
        "fs/ecryptfs/mmap.c:ecryptfs_writepage",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191197,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585249269,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287749,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330898,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585647484,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863973,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586363394,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586380785,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586431377,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586749441,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586842917,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_account_pin",
        "io_uring/rsrc.c:io_buffer_account_pin",
        "io_uring/rsrc.c:io_buffer_account_pin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587048570,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:pipe_get_pages",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:page_copy_sane"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588396762,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588536583,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589423826,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589434530,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589946412,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589982923,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590851334,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591013691,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591169878,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591373852,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591449399,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592441119,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592493532,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593082872,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593104626,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593181506,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:__skb_zcopy_downgrade_managed",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:skb_add_rx_frag",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593197890,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593521418,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593552233,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593562362,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0",
        "net/core/gro.c:skb_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593590917,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_skb_page",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593816912,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594161517,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594254209,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_build_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594326918,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594735616,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594806642,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594869631,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594929614,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595404800,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595544640,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595604185,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595749501,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:249",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730512,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583061136,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583280176,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583320976,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583357216,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583425920,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int _compound_head(const struct page * page)
```

```json
{
  "name": "_compound_head",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619225637,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_root_generic",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578861637,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579443196,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453474,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579884430,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898858,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580523084,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974437,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347382,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427023,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520502,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550930,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582575608,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617444,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637205,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/folio-compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:lru_cache_add_inactive_or_unevictable",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_writeback",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:wait_for_stable_page",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:end_page_writeback",
        "mm/folio-compat.c:unlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582651975,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663030,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742147,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:get_pfn_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770473,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_swapin",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582794613,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:page_rmapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865615,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__ksize",
        "mm/slab_common.c:kfree",
        "mm/slab_common.c:kmem_dump_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887097,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:pageblock_skip_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582916325,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582939514,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:migrate_longterm_unpinnable_pages",
        "mm/gup.c:migrate_longterm_unpinnable_pages",
        "mm/gup.c:migrate_longterm_unpinnable_pages",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995171,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:numa_migrate_prep",
        "mm/memory.c:vm_insert_pages",
        "mm/memory.c:vm_insert_pages",
        "mm/memory.c:vm_insert_pages",
        "mm/memory.c:vm_normal_folio"
      ],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:pfn_swap_entry_to_page"
      ]
    },
    {
      "addr": 18446744071583012724,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583015340,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050053,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:can_change_pte_writable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583068514,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583102565,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_anon_rmap",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_move_anon_rmap",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135022,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583185943,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:free_contig_range",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:move_freepages_block",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596964189,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583208372,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583215590,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:swap_writepage_fs",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:bio_associate_blkg_from_page",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:__end_swap_bio_read",
        "mm/page_io.c:__end_swap_bio_read",
        "mm/page_io.c:__end_swap_bio_write",
        "mm/page_io.c:__end_swap_bio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221825,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:free_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235208,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255252,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266233,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304911,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_fresh_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_basepage_index",
        "mm/hugetlb.c:hugetlb_basepage_index",
        "mm/hugetlb.c:PageHuge",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page"
      ]
    },
    {
      "addr": 18446744071583339754,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:migrate_folio_add",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:queue_folios_hugetlb",
        "mm/mempolicy.c:queue_folios_hugetlb",
        "mm/mempolicy.c:queue_folios_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596996363,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401125,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:collect_procs_ksm",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm_pmd_entry",
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583439262,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free",
        "mm/slub.c:cache_from_obj",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583452953,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481109,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497593,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536370,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:can_change_pmd_writable",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    },
    {
      "addr": 18446744071583567087,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:set_huge_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:alloc_charge_hpage",
        "mm/khugepaged.c:alloc_charge_hpage",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071583622103,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:mem_cgroup_from_slab_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": [
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    },
    {
      "addr": 18446744071583640609,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669200,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/memory-failure.c:truncate_error_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:__add_to_kill",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674852,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687436,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583693350,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583695501,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583697715,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705777,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_folio",
        "mm/page_idle.c:page_idle_get_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707118,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:check_heap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711286,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init",
        "mm/memremap.c:free_zone_device_page",
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583718276,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583802257,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813453,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:generic_pipe_buf_get",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828533,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584018277,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584042327,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584068500,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584135109,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_commit_write",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584149921,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:clean_page_buffers",
        "fs/mpage.c:clean_page_buffers",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/mpage.c:mpage_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584154229,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584257069,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_free_ring",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584297731,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584327119,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/crypto/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/bio.c:fscrypt_decrypt_bio",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584339437,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584343600,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420351,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584433508,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584505116,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584602407,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584611563,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:kpagecount_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859487,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584883091,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584984370,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584985146,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585284481,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/squashfs/block.c:squashfs_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585295809,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307686,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309710,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585331938,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585419262,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_read_folio",
        "fs/ecryptfs/mmap.c:ecryptfs_writepage",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420252,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585479013,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518027,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585560901,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585877583,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095912,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586608770,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586627103,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587011068,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587102983,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "io_uring/kbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587116474,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_buffer_account_pin",
        "io_uring/rsrc.c:io_buffer_account_pin",
        "io_uring/rsrc.c:io_buffer_account_pin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587313280,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_to_iter_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588672749,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816391,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589722978,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589733314,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590255676,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590292523,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591193952,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591367163,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591529221,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591731656,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591772606,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_rq_free_unused_buf",
        "drivers/net/virtio_net.c:virtnet_rq_free_unused_buf",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:page_to_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591864903,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592865307,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592922988,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593555986,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593610076,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_splice_from_iter",
        "net/core/skbuff.c:skb_splice_from_iter",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:__skb_zcopy_downgrade_managed",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:skb_add_rx_frag",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593657438,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593987034,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594022404,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594030949,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0",
        "net/core/gro.c:skb_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594064101,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_skb_page",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594192312,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594549558,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594640943,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594726519,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_clone_payload",
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595123059,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595199070,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595261744,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595321391,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595802755,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596060108,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596112991,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596273808,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:243",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946608,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583271344,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583499648,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583539648,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583576640,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int _compound_head(const struct page * page)
```

```json
{
  "name": "_compound_head",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621515461,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_root_generic",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578872145,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472748,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483394,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579867911,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579920705,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937562,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580584620,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068938,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454422,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593311,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689381,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721522,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582744552,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582788964,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808437,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/folio-compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_writeback",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:wait_for_stable_page",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:end_page_writeback",
        "mm/folio-compat.c:unlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823111,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582833862,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:pagecache_isize_extended"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909723,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:get_pfn_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582945815,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036802,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__ksize",
        "mm/slab_common.c:kmem_dump_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058867,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:pageblock_skip_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583090453,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114730,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio",
        "mm/gup.c:try_grab_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583127797,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:vm_insert_pages",
        "mm/memory.c:vm_insert_pages",
        "mm/memory.c:vm_normal_folio_pmd"
      ],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_read_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:set_pte_range",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:pfn_swap_entry_to_page"
      ]
    },
    {
      "addr": 18446744071583192097,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583194988,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583227248,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_rmap_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583233219,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:can_change_pte_writable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250413,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269588,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:vma_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318078,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583370068,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:free_contig_range",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:move_freepages_block",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_tail_page_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597891549,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423698,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583443940,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583450360,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_read_folio_fs",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:swap_writepage_fs",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:__end_swap_bio_read",
        "mm/page_io.c:__end_swap_bio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454798,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:free_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468773,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_index",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583542783,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:__alloc_fresh_hugetlb_folio",
        "mm/hugetlb.c:PageHuge"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_follow_page_mask"
      ]
    },
    {
      "addr": 18446744071583592436,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_folio_add",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:queue_folios_hugetlb",
        "mm/mempolicy.c:queue_folios_hugetlb",
        "mm/mempolicy.c:queue_folios_hugetlb",
        "mm/mempolicy.c:queue_folios_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597925846,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583640597,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:collect_procs_ksm",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm_pmd_entry",
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583644512,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583673544,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690742,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730069,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:can_change_pmd_writable",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071583755465,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:set_huge_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583816772,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:mem_cgroup_from_slab_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": [
        "mm/memcontrol.c:get_mctgt_type"
      ]
    },
    {
      "addr": 18446744071583834935,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583863744,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:is_raw_hwpoison_page_in_hugepage",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/memory-failure.c:has_extra_refcount",
        "mm/memory-failure.c:has_extra_refcount",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:__add_to_kill",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": [
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    },
    {
      "addr": 18446744071583869124,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880254,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583887734,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904590,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583906113,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_folio",
        "mm/page_idle.c:page_idle_get_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583907458,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:check_heap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583911654,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init",
        "mm/memremap.c:free_zone_device_page",
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583918897,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584008465,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019437,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:generic_pipe_buf_get",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_try_steal",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034949,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230362,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584257127,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584284806,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584358217,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_commit_write",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362052,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:bio_first_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584368421,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584473857,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_free_ring",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584514555,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584542852,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/crypto/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/bio.c:bio_first_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584557645,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584562335,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584641251,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584655162,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584734457,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_category",
        "fs/proc/task_mmu.c:pagemap_thp_category",
        "fs/proc/task_mmu.c:pagemap_thp_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate",
        "fs/proc/task_mmu.c:smaps_page_accumulate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584834415,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584843491,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:kpagecount_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092415,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585143995,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585215858,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585217223,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515976,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518113,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/squashfs/block.c:squashfs_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585529634,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585541750,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585543992,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585654062,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_read_folio",
        "fs/ecryptfs/mmap.c:ecryptfs_writepage",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655037,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714037,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754923,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585799305,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586126255,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345016,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586878578,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586884516,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_first_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587206422,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_map_user",
        "block/bio-integrity.c:bio_integrity_map_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587296659,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587395169,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_buffer_account_pin",
        "io_uring/rsrc.c:io_buffer_account_pin",
        "io_uring/rsrc.c:io_buffer_account_pin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587598887,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_to_iter_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973389,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589109127,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590060914,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590071278,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596652,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590633739,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591540943,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591717563,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591876693,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592067709,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/gpu/drm/drm_gem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_gem.c:drm_gem_put_pages",
        "drivers/gpu/drm/drm_gem.c:drm_gem_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592475476,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/tun.c:tun_napi_alloc_frags",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592507586,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:free_receive_page_frags",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:virtnet_rq_alloc",
        "drivers/net/virtio_net.c:virtnet_rq_alloc",
        "drivers/net/virtio_net.c:virtnet_rq_unmap",
        "drivers/net/virtio_net.c:virtnet_rq_unmap",
        "drivers/net/virtio_net.c:page_to_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592604711,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593615499,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593673111,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594328658,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594385756,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_splice_from_iter",
        "net/core/skbuff.c:skb_splice_from_iter",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:__skb_zcopy_downgrade_managed",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:napi_pp_put_page",
        "net/core/skbuff.c:skb_add_rx_frag",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594435387,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594771121,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594808990,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594818037,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0",
        "net/core/gro.c:skb_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594851135,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_return_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594987752,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595352164,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595444254,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595531576,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_clone_payload",
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595939667,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596039630,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596102128,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596163354,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596653363,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596926988,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_build_skb_zerocopy",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596985763,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597158544,
      "name": "_compound_head",
      "external": false,
      "loc": "include/linux/page-flags.h:245",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122288,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583507264,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583693120,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583770096,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583841280,
      "name": "_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long unsigned int _compound_head(const struct page * page)
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
