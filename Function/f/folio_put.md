# Function: <code>folio_put</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "folio_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593802434,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360122,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367433,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579709683,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252592,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580624780,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785084,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886457,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581941890,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:folio_end_writeback",
        "mm/filemap.c:folio_end_private_2",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981649,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_write_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997478,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023775,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051637,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_page_list",
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095675,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582191304,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582218607,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286082,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291476,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367683,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466664,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582477076,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
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
      "addr": 18446744071582499134,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582525673,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582538104,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598691,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582608981,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658977,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736416,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737504,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784109,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810944,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582855174,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897172,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582916199,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923490,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931539,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934950,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019634,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032304,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583041197,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221713,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267782,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583309272,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583328496,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583344519,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349910,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451003,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507189,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:read_file_data_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583514739,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583516525,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583588559,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583605361,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_migrate_page",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583947567,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583960331,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044070,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584085928,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584129405,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335434,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584351115,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584409454,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420344,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439702,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519678,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520450,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584575781,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584610375,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650347,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585139156,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596531,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585610689,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:__bio_release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585656996,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585750830,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/core.c:read_part_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585751268,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585754135,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585755746,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585760368,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585769026,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585774505,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585777037,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777938,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778698,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585779659,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585780697,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585784760,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785607,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071586670144,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045692,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588056442,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588506344,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588535123,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589289580,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589308678,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589740068,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590762097,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590808802,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591350854,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591419345,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591710105,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591761944,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591770451,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591792650,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
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
      "addr": 18446744071592001810,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592406299,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592471885,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592854380,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592925109,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592981290,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593645899,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:dfrag_clear"
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
void folio_put(struct folio * folio)
```

```json
{
  "name": "folio_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627481902,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579431176,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441397,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579835425,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453023,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580890668,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224777,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319325,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582376834,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:filemap_get_folios",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:folio_end_writeback",
        "mm/filemap.c:folio_end_private_2",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:replace_page_cache_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417832,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_write_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433682,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457871,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519515,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:isolate_folio",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:isolate_lru_folios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570791,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582676729,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582707727,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778787,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582781639,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872883,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981435,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582991590,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
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
      "addr": 18446744071583013086,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583025301,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053493,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117469,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583132102,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182362,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261044,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__buffer_migrate_folio",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271069,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583316827,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340462,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402016,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583449386,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583470666,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583478975,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487319,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583490726,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585075,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583596656,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606909,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583801409,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583850183,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894007,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583914491,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583927945,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933039,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584028771,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migrate_folio",
        "fs/aio.c:aio_migrate_folio",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103907,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584113351,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584116073,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192801,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584202849,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584574324,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584588534,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584681542,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584718676,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584763042,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584984378,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585001227,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585066468,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080164,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585100942,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585190366,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191219,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585249285,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    },
    {
      "addr": 18446744071585289511,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330959,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863995,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586363411,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586379454,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586431396,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586534425,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
      "addr": 18446744071586536549,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586537802,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
      "addr": 18446744071586542560,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
      "addr": 18446744071586552546,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
      "addr": 18446744071586557037,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
      "addr": 18446744071586558858,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559353,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559883,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586560455,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586561699,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586565614,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586566241,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
      "addr": 18446744071588396771,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589424299,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589437693,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589947784,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589980803,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590851641,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590873350,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591374855,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592441277,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
      "addr": 18446744071592495106,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593104646,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593152518,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593522012,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593553110,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593562375,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593586538,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
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
      "addr": 18446744071593816932,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594254231,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594326930,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594730753,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594806661,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594869657,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595577037,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595749517,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1253",
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
      "addr": 18446744071585240480,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void folio_put(struct folio * folio)
```

```json
{
  "name": "folio_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619225656,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_root_generic",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579443208,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453490,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579884452,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523103,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974558,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427031,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520515,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
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
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582585076,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:filemap_get_folios",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:filemap_get_entry",
        "mm/filemap.c:folio_end_writeback",
        "mm/filemap.c:folio_end_private_2",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:replace_page_cache_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582638839,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663089,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721172,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:isolate_lru_folios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778148,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_get_partial_folio",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582888348,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582922222,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995193,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_present_pte"
      ]
    },
    {
      "addr": 18446744071582997989,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087168,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193320,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202163,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221848,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235227,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266255,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583327889,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:folio_putback_active_hugetlb",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    },
    {
      "addr": 18446744071583342313,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399823,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481162,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_done",
        "mm/migrate.c:__buffer_migrate_folio",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491485,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535273,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561675,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622125,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669213,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    },
    {
      "addr": 18446744071583687641,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583695522,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702940,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    },
    {
      "addr": 18446744071583706179,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583802273,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813469,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828557,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584018366,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584068520,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584116983,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584137821,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:__find_get_block_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145839,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584257779,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migrate_folio",
        "fs/aio.c:aio_migrate_folio",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584339453,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584341763,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420373,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584432800,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584800988,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    },
    {
      "addr": 18446744071584816777,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584899971,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584941877,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584986793,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209764,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585235259,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585284534,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585295828,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309780,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330614,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585419422,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420274,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585479029,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    },
    {
      "addr": 18446744071585519767,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585560962,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095928,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586608787,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586781142,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
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
      "addr": 18446744071586784621,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586787039,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
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
      "addr": 18446744071586793313,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
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
      "addr": 18446744071586803666,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
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
      "addr": 18446744071586810652,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071586813080,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586813996,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586815103,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586816116,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586817811,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822242,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822995,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
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
      "addr": 18446744071588672758,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589723451,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589735578,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590257049,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590290427,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591193964,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591216531,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591731806,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591772625,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_rq_free_unused_buf",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:page_to_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592865465,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
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
      "addr": 18446744071592925378,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593556006,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593650882,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593987628,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594022422,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594030966,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594059562,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
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
      "addr": 18446744071594192332,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594640966,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594716501,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595123085,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595199090,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595261773,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596087017,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596273824,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1437",
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
      "addr": 18446744071582946800,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583275536,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583646928,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583696512,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584791936,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585470288,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void folio_put(struct folio * folio)
```

```json
{
  "name": "folio_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621515480,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_root_generic",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472760,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483410,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579920727,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584639,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069113,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key",
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593319,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689394,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
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
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582756500,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_folio",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:filemap_get_entry",
        "mm/filemap.c:folio_end_writeback",
        "mm/filemap.c:folio_end_private_2",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:replace_page_cache_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810008,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582833921,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582890565,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:isolate_lru_folios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954386,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_alloc_and_add_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_get_partial_folio",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059592,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096331,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583127814,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_read_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_present_pte"
      ]
    },
    {
      "addr": 18446744071583177397,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269632,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583378234,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583386824,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:free_large_kmalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437704,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583457179,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": [
        "mm/swap_state.c:__read_swap_cache_async"
      ]
    },
    {
      "addr": 18446744071583471492,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583498411,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
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
      "addr": 18446744071583564079,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:folio_putback_active_hugetlb",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583578493,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583639790,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583673794,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_done",
        "mm/migrate.c:__buffer_migrate_folio",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690538,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
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
      "addr": 18446744071583729319,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071583750008,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583816794,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583863756,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    },
    {
      "addr": 18446744071583880458,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583889684,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902887,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages_pte",
        "mm/userfaultfd.c:move_pages_pte",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    },
    {
      "addr": 18446744071583906515,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584008481,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019453,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034969,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230441,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584284826,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584334869,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584353871,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:__find_get_block_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361612,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584474562,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migrate_folio",
        "fs/aio.c:aio_migrate_folio",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584557661,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584560288,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584641266,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584654523,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:ifs_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585033884,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    },
    {
      "addr": 18446744071585049783,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585144017,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585173350,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585218422,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585442642,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585468530,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518166,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585529653,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585544062,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585565396,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585654222,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655059,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714053,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    },
    {
      "addr": 18446744071585756631,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585799366,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345032,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586878595,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587057894,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
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
      "addr": 18446744071587061373,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587063791,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
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
      "addr": 18446744071587070145,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
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
      "addr": 18446744071587080658,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
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
      "addr": 18446744071587087692,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071587090120,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587091036,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587092143,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587093156,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587094851,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587099330,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587100083,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
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
      "addr": 18446744071587303355,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588973398,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590061387,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590073034,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590598025,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590631563,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591540955,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591563715,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592475626,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592507598,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:free_receive_page_frags",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:virtnet_rq_unmap",
        "drivers/net/virtio_net.c:page_to_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593615657,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593676034,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594328678,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594426658,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594771715,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594809008,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594818054,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594849981,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594987772,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595444277,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595523045,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595939693,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596039650,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596102157,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596955753,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597158560,
      "name": "folio_put",
      "external": false,
      "loc": "include/linux/mm.h:1491",
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
      "addr": 18446744071583122800,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583451648,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583695840,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583841584,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583890720,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585024800,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585705312,
      "name": "folio_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void folio_put(struct folio * folio)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
