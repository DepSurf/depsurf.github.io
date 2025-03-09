# Function: <code>put_devmap_managed_page</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602755414,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450046,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818404,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058885,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580740285,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "kernel/bpf/sockmap.c:free_sg",
        "kernel/bpf/sockmap.c:free_bytes_sg",
        "kernel/bpf/sockmap.c:bpf_tcp_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580749183,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580812974,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580838814,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849276,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868144,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:filemap_range_has_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580935540,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941971,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951017,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957324,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985782,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:putback_inactive_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015486,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101060,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:get_user_pages_longterm",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143485,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146458,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151241,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200668,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581221086,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581224630,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_inject_error",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238970,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259280,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_vma",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581271031,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304518,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315926,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339150,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225424,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400818,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:buffer_migrate_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440309,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457268,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479306,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071581508862,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523185,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532713,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536965,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071581538240,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564654,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581604465,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581612682,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623703,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756561,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795111,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835091,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846002,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863359,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874108,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940902,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071582016684,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582031441,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050656,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_dirty_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095774,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309041,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361218,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382562,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071582418930,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453660,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563894,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582608142,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646123,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657066,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071582672222,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739112,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740609,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582788692,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826260,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583206161,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583545787,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583667537,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677799,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071583680566,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583681733,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071583684657,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071583689526,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698326,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700243,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700724,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701492,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702143,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702838,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707284,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707916,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071585071577,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080751,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585439703,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585470826,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586097488,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586435463,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587192103,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244844,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587716651,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587765444,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
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
      "addr": 18446744071587814086,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587969753,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587998333,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588010554,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_return_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588264627,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588308631,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120699,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:862",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604549428,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483513,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865108,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106215,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813501,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879618,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907258,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:prepare_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580918078,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939311,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_entries_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012484,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017955,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027179,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033343,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062841,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:putback_inactive_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088859,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179139,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:get_user_pages_longterm",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223309,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226282,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231070,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284152,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304798,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581308169,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_inject_error",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581322384,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342247,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354215,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388184,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400583,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423077,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589469153,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484453,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523794,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537879,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569500,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071581594727,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611569,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617198,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623013,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071581624288,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651464,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689905,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581699034,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709927,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843041,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886071,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581922369,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581928514,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948776,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581959267,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582028628,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071582104636,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582119505,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142052,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_readpages",
        "fs/iomap.c:iomap_readpages_actor",
        "fs/iomap.c:iomap_readpages_actor",
        "fs/iomap.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189022,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582407761,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582460366,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497162,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518392,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553150,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665158,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582709897,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582747899,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758930,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071582774078,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842872,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844369,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892672,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582928852,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950421,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323105,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668951,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583774641,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785079,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071583787862,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789029,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071583791953,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071583796950,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805782,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583807699,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808180,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808952,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583809602,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583810294,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814260,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814892,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071585179583,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585192863,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585563159,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585594554,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586230704,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586243584,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593502,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587372199,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587425804,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587855371,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587899250,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071587948899,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588124301,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
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
      "addr": 18446744071588157913,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588171290,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_return_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588178714,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452924,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588497553,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588768302,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354331,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604643669,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501428,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899673,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580151077,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580902589,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975519,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004807,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:prepare_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033665,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581075592,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081924,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581089746,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097728,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126957,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160586,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
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
      "addr": 18446744071581249436,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:put_user_pages",
        "mm/gup.c:__put_user_pages_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296992,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300143,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305325,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358478,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384780,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581422666,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433440,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581452448,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581466204,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499839,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512736,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540873,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
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
      "addr": 18446744071581582794,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602758,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632723,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581647589,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681049,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071581706058,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581723039,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730161,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735409,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071581736640,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738391,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768969,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808402,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581816794,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581827687,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967618,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582012135,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059665,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067523,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582084395,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
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
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091924,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582165270,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071582193858,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266671,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582281350,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305655,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352392,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576496,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629346,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657690,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
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
      "addr": 18446744071582687148,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725645,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582837669,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582883289,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923556,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582933165,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071582948502,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017959,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019167,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583068324,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583107655,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583132404,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510621,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856338,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:__bio_add_pc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583964475,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583974871,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071583977402,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071583978904,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071583981861,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071583988653,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995881,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583997680,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998227,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583999013,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583999666,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584000404,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004392,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005020,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071585391886,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585406282,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585782923,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585814328,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586473954,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586487241,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586846837,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587645466,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587697712,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588159813,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205278,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071588258385,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588460627,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
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
      "addr": 18446744071588479436,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588497217,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_request_shutdown",
        "net/core/page_pool.c:__page_pool_request_shutdown",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588504798,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588858935,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588906334,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201336,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589811369,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:959",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655930,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527650,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949897,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198735,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955771,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029647,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059658,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:prepare_uprobe",
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
      "addr": 18446744071581089233,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131576,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581137908,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146466,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581154226,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181374,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581218506,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
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
      "addr": 18446744071581308044,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355760,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358847,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363901,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418147,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445724,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581483704,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497680,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516667,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528805,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564351,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577104,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605769,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
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
      "addr": 18446744071581646889,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664670,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703763,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722683,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753017,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581779498,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581796608,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581803714,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808929,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581810160,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581811920,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841383,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880994,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581889354,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900247,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582040706,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090103,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127016,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:drop_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582145155,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582161833,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
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
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169300,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243510,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582257304,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582316325,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582323502,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582366061,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380436,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404679,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582451288,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582677456,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582730474,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759674,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
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
      "addr": 18446744071582789340,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828636,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582941813,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582969684,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582989832,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583030100,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039760,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071583055158,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124151,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125359,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178372,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583213143,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238704,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616509,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958581,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584067834,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078231,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584081201,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584082280,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584085237,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584092029,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584099245,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584101040,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584101587,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102373,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103026,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103760,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584107752,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584108380,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071585532536,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585547018,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585925627,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585956968,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586621746,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586635033,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586998325,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587050207,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587849562,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587902000,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588365064,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588410363,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588463505,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588666255,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588684841,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588705517,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588713646,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589082583,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589130594,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589426664,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589483035,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
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
void put_devmap_managed_page(struct page * page)
```

```json
{
  "name": "put_devmap_managed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328656,
      "name": "put_devmap_managed_page",
      "external": true,
      "loc": "mm/swap.c:1154",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:put_page",
        "kernel/exit.c:do_exit",
        "kernel/power/swap.c:hib_end_io",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/uprobes.c:is_trap_at_addr",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:copy_insn",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:write_one_page",
        "mm/readahead.c:page_cache_readahead_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_complete_page2",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:put_compound_head",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:zap_pte_range",
        "mm/mincore.c:mincore_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_inject_error",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/mempolicy.c:lookup_node",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
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
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page",
        "mm/memremap.c:memunmap_pages",
        "fs/exec.c:copy_string_kernel",
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/libfs.c:simple_write_end",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/buffer.c:drop_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/block_dev.c:blkdev_write_end",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_readahead",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:read_file_data_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead_actor",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/jbd2/commit.c:release_buffer_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_read_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/partitions/core.c:read_part_sector",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
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
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/grant-table.c:gnttab_end_foreign_access",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/scsi/scsicam.c:scsi_bios_ptable",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev",
        "net/core/sock.c:__sk_destruct",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/core/xdp.c:__xdp_return",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_empty_ring",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:page_pool_refill_alloc_cache",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__pskb_trim_head",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clear_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328656,
      "name": "put_devmap_managed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void put_devmap_managed_page(struct page * page)
```

```json
{
  "name": "put_devmap_managed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369808,
      "name": "put_devmap_managed_page",
      "external": true,
      "loc": "mm/swap.c:1147",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:put_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "kernel/exit.c:do_exit",
        "kernel/power/swap.c:hib_end_io",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/uprobes.c:is_trap_at_addr",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:copy_insn",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:generic_file_buffered_read_pagenotuptodate",
        "mm/filemap.c:generic_file_buffered_read_pagenotuptodate",
        "mm/filemap.c:generic_file_buffered_read_readpage",
        "mm/filemap.c:generic_file_buffered_read_readpage",
        "mm/filemap.c:generic_file_buffered_read_readpage",
        "mm/filemap.c:generic_file_buffered_read_readpage",
        "mm/filemap.c:generic_file_buffered_read_readpage",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:write_one_page",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_complete_page2",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:put_compound_head",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:get_shadow_from_swap_cache",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/mempolicy.c:lookup_node",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
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
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:isolate_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page",
        "mm/memremap.c:memunmap_pages",
        "fs/exec.c:copy_string_kernel",
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/libfs.c:simple_write_end",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/buffer.c:drop_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/block_dev.c:blkdev_write_end",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_zero_block",
        "fs/direct-io.c:dio_zero_block",
        "fs/mpage.c:mpage_readahead",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:read_file_data_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/coredump.c:dump_user_range",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead_actor",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/jbd2/commit.c:release_buffer_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_read_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/partitions/core.c:read_part_sector",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
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
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/grant-table.c:gnttab_end_foreign_access",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/scsi/scsicam.c:scsi_bios_ptable",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev",
        "net/core/sock.c:__sk_destruct",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/core/xdp.c:__xdp_return",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_empty_ring",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:page_pool_refill_alloc_cache",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__pskb_trim_head",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clear_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369808,
      "name": "put_devmap_managed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void put_devmap_managed_page(struct page * page)
```

```json
{
  "name": "put_devmap_managed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392736,
      "name": "put_devmap_managed_page",
      "external": true,
      "loc": "mm/swap.c:1148",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:put_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "kernel/exit.c:do_exit",
        "kernel/power/swap.c:hib_end_io",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_map_pmd",
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
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:end_page_private_2",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:write_one_page",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:put_compound_head",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
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
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page",
        "mm/memremap.c:memunmap_pages",
        "fs/exec.c:copy_string_kernel",
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/libfs.c:simple_write_end",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/block_dev.c:blkdev_write_end",
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
        "fs/direct-io.c:dio_zero_block",
        "fs/direct-io.c:dio_zero_block",
        "fs/mpage.c:mpage_readahead",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:read_file_data_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/coredump.c:dump_user_range",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead_actor",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_show",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/jbd2/commit.c:release_buffer_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/partitions/core.c:read_part_sector",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
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
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "lib/buildid.c:build_id_parse",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/grant-table.c:gnttab_end_foreign_access",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/scsi/scsicam.c:scsi_bios_ptable",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev",
        "net/core/sock.c:__sk_destruct",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/core/xdp.c:__xdp_return",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:page_pool_refill_alloc_cache",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__pskb_trim_head",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clear_xmit",
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392736,
      "name": "put_devmap_managed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void put_devmap_managed_page(struct page * page)
```

```json
{
  "name": "put_devmap_managed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642416,
      "name": "put_devmap_managed_page",
      "external": true,
      "loc": "mm/swap.c:1139",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:put_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "kernel/exit.c:do_exit",
        "kernel/power/swap.c:hib_end_io",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/events/core.c:perf_virt_to_phys",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
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
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:end_page_private_2",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:write_one_page",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "mm/readahead.c:read_cache_pages_invalidate_page",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:put_compound_head",
        "mm/memory.c:put_page",
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/mempolicy.c:lookup_node",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:unstable_tree_search_insert",
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
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:page_handle_poison",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage",
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page",
        "mm/memremap.c:memunmap_pages",
        "fs/exec.c:copy_string_kernel",
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/libfs.c:simple_write_end",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
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
        "fs/direct-io.c:dio_zero_block",
        "fs/direct-io.c:dio_zero_block",
        "fs/mpage.c:mpage_readahead",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:read_file_data_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/coredump.c:dump_user_range",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read",
        "fs/jbd2/commit.c:release_buffer_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "block/fops.c:blkdev_write_end",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/partitions/core.c:read_part_sector",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
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
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "lib/buildid.c:build_id_parse",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/grant-table.c:gnttab_end_foreign_access",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/scsi/scsicam.c:scsi_bios_ptable",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:export_rdev",
        "net/core/sock.c:__sk_destruct",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/core/xdp.c:__xdp_return",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:page_pool_refill_alloc_cache",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__pskb_trim_head",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642416,
      "name": "put_devmap_managed_page",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593802398,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360120,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071579367431,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579709678,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252590,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580624775,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071581785082,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886455,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071581938968,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997473,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582012392,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023773,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046635,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095673,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582191299,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582218605,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286077,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291474,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466659,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582477071,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582499129,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582525668,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582538099,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598686,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582608979,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658972,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582736414,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737499,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784104,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810939,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582855169,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582897167,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582916197,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582923488,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931534,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071582934948,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071583019632,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032302,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583041195,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221711,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267780,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328494,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
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
      "addr": 18446744071583344514,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071583349908,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583450998,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071583507184,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583514737,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583516520,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071583588557,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583947565,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071583973192,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071584044065,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071584085926,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584129400,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335432,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584409449,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420339,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071584439697,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519676,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520445,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584575779,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071584610373,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071584650342,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071585139151,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596529,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585610684,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071585656994,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585750828,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/core.c:read_part_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585751266,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071585754133,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071585755741,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071585760363,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071585769024,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071585774500,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
      "addr": 18446744071585777035,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777936,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778693,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585779657,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585780692,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585784755,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785602,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071586670142,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045690,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588056440,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588506342,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588535121,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589289578,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071589740066,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590762095,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071590808827,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591350849,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591419340,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071591710100,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071591761939,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591770449,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591792648,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
      "addr": 18446744071592001808,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592406294,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592471883,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592854378,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592925107,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592981285,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593645897,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1149",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627481897,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579431174,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071579441395,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071579835420,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071580453021,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071580890663,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071582224775,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071582319323,
      "name": "put_devmap_managed_page",
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
        "kernel/events/uprobes.c:__update_ref_ctr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373992,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433680,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582446975,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457869,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582567498,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582676724,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071582707725,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778782,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071582981430,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582992817,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071583013081,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583025296,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053488,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583117467,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071583132100,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583182357,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261042,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271067,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583316822,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340457,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071583402011,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583449384,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071583470664,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583478973,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583487479,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583490724,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583585073,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583596654,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583606907,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583801407,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583850181,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071583914489,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071583927940,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071584031603,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103902,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584113349,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584116068,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071584192796,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071584574322,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071584601422,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071584681537,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071584718674,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584763037,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071584984376,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071585066466,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585080159,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585100937,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585190364,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071585191214,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071585249283,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585289509,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071585330954,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071585863990,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071586363409,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071586379452,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071586431394,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071588396769,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589424297,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071589437688,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071589947782,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071589980801,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590851639,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071591374853,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071592441275,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071592495131,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593104644,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071593152516,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
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
      "addr": 18446744071593522010,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071593553105,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071593562373,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071593586536,
      "name": "put_devmap_managed_page",
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
        "net/core/page_pool.c:__page_pool_alloc_page_order",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593816930,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071594254226,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071594326928,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594730751,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071594806659,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071594869652,
      "name": "put_devmap_managed_page",
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
      "addr": 18446744071595577035,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595749515,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1201",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619225654,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_root_generic",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579443206,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071579453488,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579884447,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523101,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974553,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071582427029,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520513,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
        "kernel/events/uprobes.c:__update_ref_ctr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582652063,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663087,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582922220,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995188,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193315,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583200663,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221843,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235225,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266250,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305079,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583342311,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399818,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481160,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491483,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535268,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561670,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071583622120,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071583669211,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687639,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071583695520,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_fault",
        "mm/secretmem.c:secretmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583802271,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813467,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828555,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584018364,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584068518,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584131396,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584255931,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584339451,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584341758,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071584420368,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584899966,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071585284529,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585295826,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071585309775,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071585331955,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585419420,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420269,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585479027,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585519765,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071585560957,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071586095926,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586608785,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588672756,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589723449,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589735576,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590257047,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590290425,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591193962,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591731804,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591772623,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071592865463,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071592925403,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593556004,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593650877,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071593987626,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071594022417,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594030964,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594059560,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
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
      "addr": 18446744071594192330,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594640961,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594716499,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595123083,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595199088,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595261768,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596087015,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596273822,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1387",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621515478,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_root_generic",
        "init/do_mounts.c:do_mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472758,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071579483408,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579920722,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584637,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593317,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689392,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
        "kernel/events/uprobes.c:__update_ref_ctr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823199,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582833919,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096329,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583128346,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583378229,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454808,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471490,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583542951,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583578491,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583636950,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657750,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690536,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701869,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750003,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583816789,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071583863754,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:page_handle_poison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880456,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071584008479,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019451,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034967,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584284824,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584347284,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584472731,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584557659,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584560283,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071584641264,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585144012,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071585518161,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585529651,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071585544057,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071585654220,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655054,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714051,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756629,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071585799361,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071586345030,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586878593,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973396,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590061385,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590073032,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590598023,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:free_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590631561,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591540953,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592475624,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592507596,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071593615655,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593676059,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594328676,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594426653,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071594771713,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071594809003,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594818052,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594849979,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
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
      "addr": 18446744071594987770,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595444272,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595523043,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595939691,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596039648,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596102152,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596955751,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:dfrag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597158558,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:1441",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "arch/arm/mm/fault-armv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/binfmt_elf_fdpic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302368324,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282822848,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "arch/powerpc/mm/book3s64/iommu_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free",
        "arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283492812,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284379788,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285537868,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285639296,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285685420,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:prepare_uprobe",
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
      "addr": 13835058055285732636,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285792204,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285801080,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285815288,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285827672,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285867784,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285921984,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
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
      "addr": 13835058055286060688,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286123944,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286127712,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286135032,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286200432,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286239600,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286302940,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286324900,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286352144,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286374476,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286426072,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286440692,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286484240,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
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
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
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
      "addr": 13835058055286547104,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286581432,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286637140,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286665604,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286714396,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055286758864,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286785772,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286795976,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286802740,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055286804756,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286807624,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286846156,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:vfs_dedupe_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286901992,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286913380,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286933552,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287140776,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287216044,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287269740,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:drop_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287295932,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287321364,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
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
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287329776,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287426724,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055287450504,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287532644,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287542240,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055287602380,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287617772,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287656032,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287726708,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288055284,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288126872,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288171032,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
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
      "addr": 13835058055288213372,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288266480,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288420472,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288457500,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288488352,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288548960,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288561180,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055288583500,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288680756,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288682084,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288757772,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288805208,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288839880,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289428956,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289956252,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290120092,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290132160,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055290136120,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055290137792,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055290141828,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290153224,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290160932,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290162896,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290163944,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290165048,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290165936,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290166888,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290172228,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290173184,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055291430892,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291911300,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291952360,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292802012,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292821304,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293318804,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293381828,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/vfio/vfio_iommu_spapr_tce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294579544,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294635556,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295272660,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295346024,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055295422652,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295703176,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 13835058055295734904,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295763356,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295775972,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296310320,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296372084,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296785452,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296865988,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:990",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604582202,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501314,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917684,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580167535,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924571,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998495,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028506,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:prepare_uprobe",
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
      "addr": 18446744071581058081,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100424,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581106756,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581115314,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581123074,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150222,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187354,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
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
      "addr": 18446744071581276892,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324608,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327695,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332749,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386995,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414572,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581452552,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581466343,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485403,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497541,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533087,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545840,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574505,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
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
      "addr": 18446744071581615625,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633406,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672499,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691419,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721753,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581748234,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765344,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772450,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777665,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581778896,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780656,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810119,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849730,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581858090,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868983,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009442,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058839,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095752,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:drop_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113891,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582130569,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
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
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138036,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212246,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582226040,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582285061,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582292238,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582334797,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349172,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373415,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420024,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646192,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699210,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728410,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
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
      "addr": 18446744071582758076,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797372,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582910549,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582938420,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582958568,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998836,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583008496,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071583023894,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092887,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094095,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583147108,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181879,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583207440,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585245,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583927317,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584036570,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584046967,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584049937,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584051016,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584053973,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584060765,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584067981,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584069776,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070323,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584071109,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584071762,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072496,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076488,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584077116,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071585294568,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309050,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585686603,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585717944,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586312226,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586325513,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586755349,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480538,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587532976,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587971848,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588017147,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588070289,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272991,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588291577,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588312253,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588320382,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588688967,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588736978,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589031032,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589087403,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604573879,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430190,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579856905,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580115151,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870630,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944687,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974602,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:prepare_uprobe",
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
      "addr": 18446744071581005323,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047544,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053828,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062354,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070044,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097134,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134106,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
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
      "addr": 18446744071581223687,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268368,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581271519,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276461,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329733,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357084,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581394872,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408369,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427659,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439781,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474863,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487488,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516073,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
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
      "addr": 18446744071581556953,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574462,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611967,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581630443,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660509,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581686858,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703968,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710824,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715825,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581717056,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718816,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747783,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787394,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581795690,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806583,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947010,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581996391,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033224,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:drop_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051331,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068009,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
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
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075476,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582150022,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582163880,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582222821,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229998,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582272525,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286884,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311111,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359299,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582583360,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582636378,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665578,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
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
      "addr": 18446744071582695244,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734524,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582847701,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582875572,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582895720,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582935988,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582945648,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582961046,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583030039,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031247,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583084260,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583119031,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144592,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583522301,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583864261,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583972330,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583982727,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071583985697,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071583986776,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071583989733,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071583996525,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584003741,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005536,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006083,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006869,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584007522,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584008256,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012248,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012876,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071585247080,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585547172,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585577128,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586153554,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586166841,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586622565,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586698127,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587248698,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587301136,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587684952,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587730235,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071587783713,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587985807,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588004393,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588025037,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588033166,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588400951,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588448962,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588756072,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588812443,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604660026,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501234,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910169,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159007,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915819,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989695,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581019706,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:prepare_uprobe",
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
      "addr": 18446744071581049281,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091624,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097956,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581106514,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114274,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141422,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178554,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
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
      "addr": 18446744071581268092,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315808,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318895,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323949,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378195,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405772,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581443752,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457728,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476715,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581488853,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524399,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537152,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565817,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
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
      "addr": 18446744071581606937,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624718,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663811,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682731,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713065,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581739546,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756656,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763762,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768977,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581770208,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771968,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801431,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841042,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581849402,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581860295,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582000722,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050119,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582086232,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:drop_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582104371,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582121049,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
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
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128516,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202726,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582216520,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582275541,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582282718,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582325277,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582339652,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363895,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410504,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582636048,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689066,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718266,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
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
      "addr": 18446744071582747932,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786252,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899157,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582927028,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582947176,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987444,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997104,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071583012502,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583081495,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082703,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583131140,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583165911,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191472,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583569021,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583911077,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584020330,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584030727,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584033697,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584034776,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584037733,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584044525,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584051741,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584053536,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584054083,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584054869,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055522,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056256,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060248,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060876,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071585482936,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585497418,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585876724,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585906984,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586569714,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586583001,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586952885,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587004767,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587805706,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858144,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588303624,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588348923,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588402065,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588604815,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588623401,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588644077,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588652206,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589125143,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589173154,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589467896,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589524267,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
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
  "name": "put_devmap_managed_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604660031,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533878,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579956233,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580212858,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975903,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050639,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081009,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:prepare_uprobe",
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
      "addr": 18446744071581110936,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153784,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160164,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581168786,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176719,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203966,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241770,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
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
      "addr": 18446744071581331948,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379754,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382879,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387933,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442161,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469884,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581508232,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522160,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541458,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551865,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589325,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602190,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581630833,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673337,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691070,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730179,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747814,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780602,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581807802,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823806,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581832559,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837836,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071581839072,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840880,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870613,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910566,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581918906,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932199,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071922,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582121799,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158920,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:drop_buffers",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177555,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582194041,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
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
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201572,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582276564,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582294536,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582354101,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361310,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071582404536,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418975,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582443635,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582489158,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582719360,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582773271,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582803054,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
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
      "addr": 18446744071582833212,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872648,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986229,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583014129,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583035500,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583076548,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583086272,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071583101681,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170843,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171983,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224676,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259447,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583285383,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666177,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012373,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584122874,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133223,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584136193,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584137272,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584140229,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071584147021,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584154237,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
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
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584156032,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584156579,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157365,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158018,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158752,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584162744,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584163372,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071585592120,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585605450,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_handle_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585983899,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586015768,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586681938,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695225,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587055344,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587111935,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587933306,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587977024,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588439032,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588484443,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588538545,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:gro_pull_from_frag0"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742495,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
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
      "addr": 18446744071588761404,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588783645,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588792014,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_free_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589164967,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589213186,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589513800,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589571707,
      "name": "put_devmap_managed_page",
      "external": false,
      "loc": "include/linux/mm.h:972",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
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
void put_devmap_managed_page(struct page * page)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void put_devmap_managed_page(struct page * page)
```
</details>
</li>
</ul>
