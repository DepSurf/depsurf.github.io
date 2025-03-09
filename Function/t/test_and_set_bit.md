# Function: <code>test_and_set_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578855189,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578882188,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934668,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_cpu_starting",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976933,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579023192,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079250,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111570,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168634,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176868,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:topology_update_package_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247532,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308213,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_splitting_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389249,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action",
        "kernel/softirq.c:__hrtimer_tasklet_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446123,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469403,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:queue_delayed_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492857,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494458,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500957,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_parkme"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579625265,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587367359,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579740207,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579883153,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889093,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892407,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580088716,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580134043,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448623,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474022,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580486202,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580519153,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:__set_page_dirty_nobuffers",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580531734,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580537744,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__get_page_tail",
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580543232,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552001,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:zone_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586348,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580603627,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580608992,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580657144,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580663293,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692225,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:munlock_vma_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580713833,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730117,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756391,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580764019,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:scan_swap_map",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580806573,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830566,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580851069,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:__kmem_cache_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880622,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897838,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580925310,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949762,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963932,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971909,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue",
        "mm/balloon_compaction.c:balloon_page_isolate",
        "mm/balloon_compaction.c:balloon_page_putback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975926,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581026993,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086848,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_drop",
        "fs/dcache.c:__d_obtain_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198249,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:__generic_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215077,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326535,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:__dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387740,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_entry_find_next",
        "fs/mbcache.c:mb_cache_entry_find_first",
        "fs/mbcache.c:mb_cache_entry_free",
        "fs/mbcache.c:mb_cache_entry_free",
        "fs/mbcache.c:mb_cache_entry_insert",
        "fs/mbcache.c:mb_cache_entry_insert",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:mb_cache_shrink_scan",
        "fs/mbcache.c:mb_cache_shrink_scan",
        "fs/mbcache.c:mb_cache_entry_alloc",
        "fs/mbcache.c:mb_cache_entry_alloc",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402857,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_bdq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531347,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541512,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581545760,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557763,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595423,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699237,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724535,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749902,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825364,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831741,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847785,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859439,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581881488,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto.c:ext4_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581899742,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909595,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915687,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931833,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595192905,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581940128,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008477,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055045,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081557,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582184715,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215016,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582608031,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582654783,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "crypto/chainiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/chainiv.c:async_chainiv_givencrypt",
        "crypto/chainiv.c:async_chainiv_givencrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760654,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-tag.c:blk_queue_start_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785365,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-softirq.c:blk_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785995,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-timeout.c:blk_rq_timed_out_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786696,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-iopoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iopoll.c:blk_iopoll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582794245,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582806193,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964599,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187059,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:__gpiod_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220978,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583225684,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511945,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583578026,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583990766,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583996434,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584031776,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056288,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584238821,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584263737,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584484189,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584722423,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584741903,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584758981,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/dma-buf/fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/fence.c:fence_signal_locked",
        "drivers/dma-buf/fence.c:fence_add_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584840843,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584958685,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585061596,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074701,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:skb_recv_done",
        "drivers/net/virtio_net.c:virtnet_netpoll",
        "drivers/net/virtio_net.c:virtnet_busy_poll",
        "drivers/net/virtio_net.c:virtnet_busy_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585119880,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585169177,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585189786,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585262943,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420560,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585610832,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_irq_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585616775,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585706262,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585780741,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585865956,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586274941,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586383514,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586399240,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush_per_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586418566,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586452149,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586487686,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586662968,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586684610,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586701211,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586893897,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv4/tcp_memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_memcontrol.c:tcp_cgroup_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587173402,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578855285,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578882904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932392,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_cpu_starting",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976917,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579019880,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075182,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111340,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169104,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177303,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:topology_update_package_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247152,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403797,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "kernel/softirq.c:tasklet_kill",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458799,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579484315,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506856,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579508602,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515043,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_parkme"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579639570,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587868103,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579762533,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912699,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919198,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579924250,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580122237,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580168139,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580530594,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554283,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580569773,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605603,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580618101,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580629104,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580632003,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
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
      "addr": 18446744071580663745,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580682971,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580712336,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580766615,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580774455,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807278,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580812128,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580848780,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871895,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877214,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580878753,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891859,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930605,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938161,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962921,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993281,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:free_debug_processing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015447,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040839,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052189,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581076864,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105566,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122162,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126384,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581129930,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581186136,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252451,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_lookup_done",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363911,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:__generic_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391787,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498051,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502769,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567608,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_block",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581708,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581586990,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_bdq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716995,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727318,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581731553,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581784394,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786134,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891325,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581919362,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944577,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021302,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027766,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045404,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055200,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085688,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582087928,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096749,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102377,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124687,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595367952,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582154084,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582221676,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266853,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294372,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401035,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433472,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582855175,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582876874,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583038679,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-tag.c:blk_queue_start_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583063781,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-softirq.c:blk_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583064447,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-timeout.c:blk_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070501,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583086401,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251863,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583440943,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487738,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:__gpiod_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583533767,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833677,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595411648,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583900963,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584322878,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584328882,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584375415,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584385669,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584578670,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604760,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584830116,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074665,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585094221,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585115893,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/dma-buf/fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/fence.c:fence_add_callback",
        "drivers/dma-buf/fence.c:fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585203507,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585325917,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585451070,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585466410,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_netpoll",
        "drivers/net/virtio_net.c:virtnet_busy_poll",
        "drivers/net/virtio_net.c:virtnet_busy_poll",
        "drivers/net/virtio_net.c:skb_recv_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518227,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585565927,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585581894,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585658299,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585816467,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586006091,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_irq_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586012215,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586105834,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586178773,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586267737,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586700672,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586819671,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586841816,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush_per_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586861629,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586898277,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586934006,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109384,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134296,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587148778,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587631442,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587813173,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817654,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:204",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_add_filter"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578855317,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578882968,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933240,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978645,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579020292,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073854,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109891,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179344,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187848,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:topology_update_package_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259552,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424325,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "kernel/softirq.c:tasklet_kill",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504891,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527528,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529270,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535685,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_parkme"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664160,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588082279,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789506,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943242,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949786,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954906,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580162573,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580208318,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580210744,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580594573,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580619080,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634607,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580672753,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580685173,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580696320,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699235,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
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
      "addr": 18446744071580731025,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580750018,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580778160,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580832178,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849952,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872327,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877485,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580919260,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939783,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945250,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580946830,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960262,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998908,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009910,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581036581,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067105,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:free_debug_processing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581089793,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116007,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132388,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152464,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180730,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197237,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201424,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581205018,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581222370,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581263352,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330243,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_lookup_done",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437348,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581470203,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581278,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:grab_mapping_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587967,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581652214,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_block",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670588,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675374,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_bdq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581804627,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581813862,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581819153,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581873946,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875718,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581980733,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009426,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034609,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111398,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117894,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135249,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144832,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175784,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178024,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186845,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192473,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214463,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595616298,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582243506,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311212,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358517,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382756,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493227,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582525664,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582949199,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582974330,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583143300,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-tag.c:blk_queue_start_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170933,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-softirq.c:blk_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171599,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-timeout.c:blk_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583180117,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583194625,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367217,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583566815,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572484,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583626698,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:__gpiod_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669847,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583972925,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595661508,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584041471,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504910,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510834,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584557255,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584568549,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584760142,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786424,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585023344,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585259947,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585281805,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585305340,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585314149,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585398211,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585433788,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_write_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585526957,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655152,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585753607,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585769542,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585846008,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586005139,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586201899,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_irq_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586208023,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586306698,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586382645,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586471818,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586887808,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587007479,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587032744,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush_per_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587052715,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587092469,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587129206,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587307296,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587332888,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587347827,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587836045,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588026597,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588031398,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_add_filter"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578854181,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578882168,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926328,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979301,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579014340,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067516,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101574,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178027,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186154,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:topology_update_package_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255271,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411893,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "kernel/softirq.c:tasklet_kill",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579493931,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515092,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516806,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522927,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_parkme"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638729,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588309454,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787027,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952349,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579957722,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579959819,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168781,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580216382,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218955,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580624646,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648856,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580664025,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710402,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718693,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580730096,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732735,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
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
      "addr": 18446744071580766904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785405,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813968,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580872828,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895341,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917332,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922157,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580963529,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984013,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989495,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580991453,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006406,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047601,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057300,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084397,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581115082,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:free_debug_processing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581137199,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
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
      "addr": 18446744071581164194,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175212,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581199792,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228242,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244916,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248867,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581253818,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581270067,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581312440,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386003,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_lookup_done",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491988,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533068,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648565,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581706654,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724652,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730232,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_bdq",
        "fs/quota/dquot.c:check_idq",
        "fs/quota/dquot.c:check_idq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875919,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897029,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930871,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581942929,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581957247,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964680,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021982,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582073716,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112242,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118886,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197139,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238761,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582262264,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264438,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272779,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582278329,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582299631,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596546703,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582328748,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396076,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582442437,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467735,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574125,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582609252,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582999311,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583023914,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583200381,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-tag.c:blk_queue_start_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583228213,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-softirq.c:blk_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583228876,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-timeout.c:blk_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242580,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250865,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258476,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583604175,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609899,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_get_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583670794,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:__gpiod_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583709856,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584021486,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596584787,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102616,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584584222,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584589621,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584639354,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650137,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584842028,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584875510,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584974550,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585108325,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585343243,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585367105,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585394386,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585403113,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585482755,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518039,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585611389,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585741669,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585840509,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585856126,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585932467,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586088906,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586290624,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_irq_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586297287,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586404666,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426247,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586480549,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586584439,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012745,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587133367,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587160616,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush_per_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587180579,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221029,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587259702,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587441370,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587465240,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480625,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587993170,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184677,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588189509,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_add_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216273,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:217",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578854233,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578883724,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928715,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578982280,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579014884,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033811,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076620,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113043,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193611,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272039,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439433,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "kernel/softirq.c:tasklet_kill",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579520651,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579542956,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549306,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_parkme"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669291,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588874814,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820433,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579866827,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579998045,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003520,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006756,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221185,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580267668,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580269924,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580705565,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732675,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580749072,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795952,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580804229,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580816096,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819411,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
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
      "addr": 18446744071580854248,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580874735,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904064,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580969331,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993095,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016740,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581021777,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581065849,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087027,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093213,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095437,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119230,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158266,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581196116,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226106,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:free_debug_processing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254082,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
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
      "addr": 18446744071581290722,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308794,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329712,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359350,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376552,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380563,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581385882,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581388899,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409064,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581452472,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525667,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_lookup_done",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_rehash",
        "fs/dcache.c:___d_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610939,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581633940,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675745,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581794005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581852286,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870687,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875806,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582025919,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047205,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092241,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106303,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113736,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172590,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582261250,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268038,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345891,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387628,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411304,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413481,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421931,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427465,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582448671,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602874134,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582479041,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582546764,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582592990,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582618471,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582726859,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582762820,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583163407,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583188986,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583376509,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-tag.c:blk_queue_start_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583404905,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-softirq.c:blk_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583405526,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-timeout.c:blk_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583411881,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583430241,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583438114,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583849887,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583855947,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_get_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583925514,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583967248,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584237406,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602912975,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584374072,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584996302,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585001690,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585051770,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585062601,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585262636,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585295046,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585395774,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585534517,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585771643,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585794881,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585823923,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831567,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585914195,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585949751,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586042986,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586175384,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586279901,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586296046,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586374275,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586533296,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586662856,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586754105,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_irq_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586760803,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586870890,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586948156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587067687,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587510697,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587636983,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587685398,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587734921,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587779174,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587962639,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_wfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587987297,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588002654,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277973,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588529622,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588735685,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_add_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766225,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578856037,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578885519,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931586,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985685,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579017572,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038035,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081956,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119395,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121366,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205424,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283127,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454773,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579541205,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579570652,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589253630,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853809,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900955,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580050150,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056097,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058792,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580281216,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580328015,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330677,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580838203,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868099,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884912,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580935904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941141,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580953091,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956473,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
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
      "addr": 18446744071580991761,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011153,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039949,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581099103,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127309,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151195,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157197,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581204727,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229980,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233930,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236142,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255529,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301462,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341769,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373869,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:__slab_free",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:free_debug_processing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400294,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:buffer_migrate_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437749,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447580,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581477684,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507909,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526329,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530563,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536360,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581539875,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564626,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581612040,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681971,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_lookup_done",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_rehash",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:___d_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769227,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581792539,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831468,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581968301,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033086,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047351,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058999,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214284,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582239583,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280728,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294676,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302125,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362488,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412916,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449314,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582455986,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535121,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578446,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582601496,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582604054,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612313,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617737,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582638383,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603047318,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:init_ramfs_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582670818,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738450,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783429,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813719,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925195,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582963043,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583368907,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396981,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583586537,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-tag.c:blk_queue_start_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615157,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-softirq.c:blk_complete_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615782,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-timeout.c:blk_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583641389,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583649602,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583793176,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584050351,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055851,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_get_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584119386,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161852,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584457933,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603084978,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592344,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585230478,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585235957,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585285801,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585297329,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585499564,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585535942,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585639307,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585778181,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586018569,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586041361,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586069907,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586078647,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586161443,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586290618,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433587,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586537527,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586553537,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632413,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586796949,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586926872,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587020848,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_irq_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034579,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587164346,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587243029,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587365175,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814746,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587947463,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588017570,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588068725,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588121590,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588311345,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588334332,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588353483,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588632978,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588891085,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589144961,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578856117,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578885311,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933122,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983285,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579019188,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042787,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087412,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124995,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229164,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307079,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488581,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578277,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607644,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589495854,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900769,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948475,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096966,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580102929,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106122,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333584,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580381067,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580383916,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580906647,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939266,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958224,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996663,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003730,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017045,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581029251,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032457,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
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
      "addr": 18446744071581068376,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084923,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117533,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581181885,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192692,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231024,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236941,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581288439,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312958,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316960,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319550,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338803,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581385103,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425836,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451909,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:__slab_free",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:free_debug_processing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581483920,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521381,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532307,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560020,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593839,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608665,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616355,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581625875,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650850,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581698392,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768627,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_lookup_done",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_rehash",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:___d_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581854053,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879435,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918716,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055213,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582121118,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141234,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/iomap.c:iomap_set_page_dirty",
        "fs/iomap.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582153751,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309132,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582335503,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379464,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582393431,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400749,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461496,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_getblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512372,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582548786,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582555513,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582636225,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_commit_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679189,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703240,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582705762,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714079,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719481,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740127,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604846575,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:init_ramfs_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582771720,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842210,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887573,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582917015,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583033723,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583075746,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583487659,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583517029,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583674184,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747661,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839355,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583873800,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133359,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138987,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_get_word"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584203313,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584249696,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584554461,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604887261,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584692680,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585178997,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585349774,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585355205,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585405849,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585419040,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585620156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585660536,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585768657,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585911381,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586157529,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586181473,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586214451,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586222919,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586254937,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586262261,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586303331,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586432186,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586582339,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586686243,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586702401,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586781485,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586954007,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587083880,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587192787,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587344266,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587545063,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949546,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588095559,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588185026,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588246037,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588303846,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588498721,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588523580,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588543972,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588848754,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589114528,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380097,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/x86/include/asm/bitops.h:218",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886555,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938891,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996581,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579026891,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579050431,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097117,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134675,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242366,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504917,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601813,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631974,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589956639,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579935610,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579987137,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140872,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146857,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580386268,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580433995,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580436754,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581004584,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053523,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068115,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093285,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131573,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182157,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581304807,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311214,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581415575,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589943434,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612465,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650553,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680122,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581978709,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582052670,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582298900,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316393,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582893145,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066741,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583215563,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258913,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583673823,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704709,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583862904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583936881,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584029563,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584065448,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584323615,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584392465,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584442881,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604993331,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584893624,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585391461,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585562942,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585569013,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585620216,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585633569,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585840844,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585886870,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586000515,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586152480,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_memory_block_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586393703,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586418436,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456735,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586466573,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586497657,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586506773,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586546469,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_logging.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586676653,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586835416,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586938980,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586957761,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587039670,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225842,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348604,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480672,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587492706,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587615184,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695637,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587819799,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259779,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588411607,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588510674,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636965,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588701638,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907760,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934084,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588954845,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283782,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589567705,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837153,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887563,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941365,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998085,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579029147,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579052671,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099101,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136595,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244526,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518320,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579530965,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579627701,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657510,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590184303,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985738,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580037265,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580189016,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194908,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580435036,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580482756,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485522,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581059077,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109523,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581124083,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189317,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240285,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581363383,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369758,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581476615,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590170989,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683377,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719161,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752076,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777462,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582053701,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582130334,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397892,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582415481,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999721,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170373,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321371,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583364801,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583780895,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814485,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583965800,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584040353,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133467,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188168,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584458303,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523169,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584579617,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605030564,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585029368,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585531973,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585704078,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585709589,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585761432,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774849,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585983564,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586029126,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586147683,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586540147,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586565200,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586604206,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586614349,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586645497,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586654661,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586823917,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586981480,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587137589,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587156449,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587240146,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587426114,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587550268,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587683844,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587695874,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587819459,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587899909,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588024567,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588464899,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588616983,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588719250,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588859333,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588925526,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589131791,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589158260,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589179133,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589508214,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589791849,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063297,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578892027,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948425,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014432,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037260,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609053633,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111597,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148409,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:wait_for_master_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268591,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547712,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579561445,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656885,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690374,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591202543,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033908,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580049865,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580088001,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254104,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580259936,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_switch_to_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580517084,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580567694,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570429,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581227643,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:xol_take_insn_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297594,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310723,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335575,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379886,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427949,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581560583,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567838,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581681773,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591189346,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901668,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581938297,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971762,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581999067,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313634,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374139,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582686916,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719674,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583316537,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583493253,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583653774,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698544,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:getoptions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584171455,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584208661,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584354088,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584435233,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584530619,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584582282,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585021823,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585060193,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585203281,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585254595,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_export_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609317295,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_initrd_scan",
        "drivers/acpi/tables.c:acpi_table_initrd_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585728091,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_enable_event",
        "drivers/acpi/ec.c:acpi_ec_submit_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252869,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433086,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586438821,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586491400,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586508495,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586724620,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765782,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586906034,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587324003,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587349840,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587391601,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587408685,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587442409,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587454565,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587662701,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587759253,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811651,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587986816,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588006401,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588094466,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588294812,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588413148,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588552466,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588564290,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588666483,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588757013,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588884087,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589330902,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:napi_hash_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589472542,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_schedule_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589586053,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589742133,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589814934,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589870326,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590099042,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590126160,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590150231,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590500677,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590810583,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591085658,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:mptcp_subflow_eof",
        "net/mptcp/protocol.c:mptcp_data_ready"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888059,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578945199,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011736,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040860,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612117127,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111437,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145497,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:wait_for_master_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270132,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275823,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579542965,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636501,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668607,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591697631,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580017467,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032441,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071367,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580237960,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243484,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_switch_to_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580505788,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580555566,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591317531,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581269883,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:xol_take_insn_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313025,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wake_page_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341642,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357751,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379116,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_inactive_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423470,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471213,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581605704,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613278,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581947198,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581985241,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582020495,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050062,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366498,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582430443,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758164,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582790812,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583154244,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431449,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583601695,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583775214,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583819808,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:getoptions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584290463,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584327045,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584471992,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584551820,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640491,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584699960,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585170607,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209633,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585359565,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585374354,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585412083,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_export_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612387888,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_initrd_scan",
        "drivers/acpi/tables.c:acpi_table_initrd_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585850235,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_enable_event",
        "drivers/acpi/ec.c:acpi_ec_submit_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586370597,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586548142,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586553349,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603896,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586621521,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586820188,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586945350,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586990901,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587385843,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587411360,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587459985,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587477485,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587511018,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587522949,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587723645,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818821,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587869638,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588046480,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588058897,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588136418,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588329829,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588443608,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577890,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588588930,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588693603,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588765437,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588777237,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588896919,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589330966,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589473406,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_schedule_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589597749,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589775221,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589851142,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589910054,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590147138,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590173824,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590198967,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590560277,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590870535,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591161034,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:mptcp_subflow_eof"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591177180,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_reset"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578890315,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950098,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018789,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579043692,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614257407,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118077,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156459,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271167,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278373,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533664,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579547659,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579643125,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675259,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591640143,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580018251,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033337,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072083,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580122749,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243193,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249011,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591259659,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581298142,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331550,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wake_page_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355921,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376947,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400076,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_inactive_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444750,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491997,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581628376,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581635694,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581973397,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582013001,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046981,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075882,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394162,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457227,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588560,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_req_task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582654408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_worker_cancel",
        "fs/io-wq.c:io_wq_worker_wake",
        "fs/io-wq.c:io_worker_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582787123,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582816898,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179451,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583453689,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583624367,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799326,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845197,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:getoptions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584324399,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361541,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584506904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584584636,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604593,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584668714,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584727689,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585050895,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092609,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585242397,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585258722,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585292819,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_export_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614531621,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init_complete",
        "drivers/acpi/tables.c:acpi_table_initrd_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585728731,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252805,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433102,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586438309,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488262,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586700188,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586724667,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586826998,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586871703,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587267971,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587293377,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587341633,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587359245,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587392666,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587403749,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587602781,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587697879,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587749974,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587928703,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587942465,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588018116,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588202926,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588326552,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588461506,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588473026,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588579971,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588651207,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588659717,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588785767,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225846,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589371902,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_schedule_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589486229,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589678853,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589756582,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589814678,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590061157,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590088688,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590113145,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590485621,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590799634,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591102640,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof",
        "net/mptcp/protocol.c:__mptcp_flush_join_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591112824,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_reset"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578891611,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969842,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036725,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579063868,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615178359,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143533,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313279,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321141,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606032,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579619931,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719733,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753467,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592814095,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580150514,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165865,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580205955,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580265424,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391566,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580399942,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592165145,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581543278,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579197,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wake_page_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603780,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625926,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650648,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_inactive_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698798,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581750828,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581896064,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581922873,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275982,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582315689,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353915,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387306,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715698,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780843,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978931,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_worker_cancel",
        "fs/io-wq.c:io_wq_worker_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583146808,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583521268,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583804281,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583983390,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161870,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584208172,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:getoptions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584711839,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584756069,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584917480,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584998908,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020081,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085082,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585155261,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585494543,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503701,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/ubsan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585540209,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585697789,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714946,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585749587,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_export_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615482304,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init_complete",
        "drivers/acpi/tables.c:acpi_table_initrd_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586210635,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763252,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586964021,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587018273,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587249548,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587276123,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587387334,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587835219,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587860129,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587908225,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587926173,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587964391,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587976005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588187213,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588289463,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588345920,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588538767,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588552929,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588634164,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843725,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588983624,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589129602,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589141234,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589255811,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589329047,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589337621,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589355326,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/dm-zone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589478970,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589948070,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590102286,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_schedule_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590226933,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590435861,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590516950,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590578134,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590834917,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590863856,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590890149,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591290010,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591617706,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591946448,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591958312,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591968011,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/options.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578894219,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980895,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579057829,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579087980,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616944273,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181290,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233932,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371055,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579380589,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698960,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579714459,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823045,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858748,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594715830,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580295528,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580312124,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580359933,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580435607,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610093,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580618729,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593938375,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581894029,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942279,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2_killable",
        "mm/filemap.c:folio_wait_private_2",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:wake_page_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963460,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581986913,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:folio_mark_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582074254,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302319,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582329521,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759627,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582807815,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853264,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892931,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260102,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583322252,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583642408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584054480,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584369177,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584564398,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584761022,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584811228,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:getoptions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585385791,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585438117,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585619304,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585711953,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585737489,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594100300,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585811626,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585890381,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586029988,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_cancel",
        "io_uring/io-wq.c:io_wq_worker_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586639647,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586652165,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/ubsan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694840,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586866173,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586889402,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586932755,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_export_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617284428,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init_complete",
        "drivers/acpi/tables.c:acpi_table_initrd_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587447979,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041456,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259093,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588318805,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588558508,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588586177,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588696982,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589187591,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589211625,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589259877,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589277671,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589320362,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589339054,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_done_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589672167,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589735963,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589947847,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589961651,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590047885,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590260449,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590416632,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590578949,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590592707,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590724515,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590800906,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590811959,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590829175,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/dm-zone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590959418,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591483788,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_napi_add_weight",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591653911,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_schedule_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591803557,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592038389,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592124246,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592195699,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592470890,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592500172,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592528288,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592956596,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593311450,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593672806,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593685432,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593697008,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/options.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578906555,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999807,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089205,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579122748,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627552705,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236650,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293180,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447274,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457069,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824112,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579841067,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579958965,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999961,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596463110,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580507096,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525484,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582845,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580677953,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580874221,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884009,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237745,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582327341,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382649,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:wake_page_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396996,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582423014,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:folio_mark_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582549710,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578572,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796847,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582804873,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583294212,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:mm_get_huge_zero_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348471,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399964,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445840,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583824197,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904848,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584247784,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_mark_dquot_dirty",
        "fs/quota/dquot.c:dquot_mark_dquot_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584686736,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020713,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585242430,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585457537,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585510076,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:getoptions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586137695,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586195829,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586389288,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586516881,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586530584,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586593360,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586678376,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock",
        "block/blk-zoned.c:blk_req_zone_write_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586865716,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_cancel",
        "io_uring/io-wq.c:io_wq_worker_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587883343,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable",
        "lib/irq_poll.c:irq_poll_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587897593,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/ubsan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587999373,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588038650,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588089955,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_export_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627994973,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_initrd_scan",
        "drivers/acpi/tables.c:acpi_table_initrd_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588712264,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589361782,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma/hsu/hsu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/hsu/hsu.c:hsu_dma_do_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589419984,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589672373,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589737541,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590011196,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590041905,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590176710,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590741853,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590767161,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590822261,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590841687,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590886077,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590905454,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_done_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591282870,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591354571,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591531895,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591552275,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591652237,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591881089,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592054252,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592236069,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592251555,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592399139,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592486520,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592498517,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592517986,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/dm-zone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592661662,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593267452,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_napi_add_weight",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593436695,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_schedule_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593598677,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593855701,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593947110,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594023939,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594326140,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594355996,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594386385,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595216363,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589905,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595616552,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595630592,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/options.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595856264,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578903963,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999583,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089429,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579123024,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619302017,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242618,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579459386,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469136,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873184,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579891051,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009653,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580053833,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168222,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597004934,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580579206,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580598480,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580655757,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754465,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958083,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580967895,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329644,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_hardlockup_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373925,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_test_and_set_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582528573,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582583297,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:wake_page_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582602868,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582628227,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:folio_mark_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582754910,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774838,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011231,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019030,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583513348,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:mm_get_huge_zero_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583567685,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583620451,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666157,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584041541,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130784,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584478395,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_mark_dquot_dirty",
        "fs/quota/dquot.c:dquot_mark_dquot_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584912231,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247977,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585472238,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585689057,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585741753,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:getoptions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586375551,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433445,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586635944,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586739716,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764129,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:blk_mark_disk_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586776632,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586851581,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586939304,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock",
        "block/blk-zoned.c:blk_req_zone_write_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131796,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_cancel",
        "io_uring/io-wq.c:io_wq_worker_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588155167,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable",
        "lib/irq_poll.c:irq_poll_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588169001,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/ubsan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588274061,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588313290,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588364371,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_export_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619760621,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_initrd_scan",
        "drivers/acpi/tables.c:acpi_table_initrd_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589000504,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589660422,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma/hsu/hsu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/hsu/hsu.c:hsu_dma_do_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589719056,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589976581,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590042373,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590320444,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590351300,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590490142,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590498662,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591083213,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591108585,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591164245,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591183751,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591229408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591249646,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_done_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591640182,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591716347,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591953815,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591973883,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592074877,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592304532,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592477063,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592661173,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592676803,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592828515,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592916409,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592928821,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592948379,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/dm-zone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593092366,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593352548,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/hid/bpf/hid_bpf_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593725260,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_napi_add_weight",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593901559,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_schedule_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594072037,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594230501,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594323366,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594401539,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594711740,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594743888,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594774721,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595612335,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596099137,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596121513,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596137488,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/options.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596226612,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596373144,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578926491,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024511,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115221,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579148880,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621595585,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271498,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579489402,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499248,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911232,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579929627,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052517,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096297,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580214510,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597934278,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580643558,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580662992,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720973,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580839585,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049667,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062631,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541253,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_test_and_set_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582697559,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582754433,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/filemap.c:wake_page_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774324,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582794741,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:folio_mark_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923134,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951022,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190351,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583198310,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583707156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:mm_get_huge_zero_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583760181,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583815382,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583860406,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584256341,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584347792,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584701355,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_mark_dquot_dirty",
        "fs/quota/dquot.c:dquot_mark_dquot_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585145159,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_prefetch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585481225,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585707262,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585936113,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_invalidate",
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585989049,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:getoptions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586640095,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586699173,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/evm/evm_crypto.c:evm_set_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586906840,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587011809,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587036609,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:__blk_mark_disk_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587053272,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587128893,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587220072,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock",
        "block/blk-zoned.c:blk_req_zone_write_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587417940,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker_cancel",
        "io_uring/io-wq.c:io_wq_worker_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588444815,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable",
        "lib/irq_poll.c:irq_poll_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588459817,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/ubsan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ubsan.c:__ubsan_handle_alignment_assumption",
        "lib/ubsan.c:__ubsan_handle_load_invalid_value",
        "lib/ubsan.c:__ubsan_handle_shift_out_of_bounds",
        "lib/ubsan.c:__ubsan_handle_out_of_bounds",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:ubsan_type_mismatch_common",
        "lib/ubsan.c:__ubsan_handle_divrem_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588566525,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588613458,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588659091,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:pwm_export_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622067997,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_initrd_scan",
        "drivers/acpi/tables.c:acpi_table_initrd_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589304808,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589970902,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma/hsu/hsu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/hsu/hsu.c:hsu_dma_do_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590056775,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590315253,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590381365,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_set_led_state",
        "drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590661788,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590692836,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590841166,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/intel/perfmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590852326,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:get_pci_alias_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591428109,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591453913,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591510229,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591530919,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591576640,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591596894,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_done_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592382054,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592460043,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592693607,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592713723,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592815149,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593045876,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593221152,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593406357,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593422227,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593577843,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593661918,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593681916,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593698270,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/md/dm-zone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593845102,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594106662,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "drivers/hid/bpf/hid_bpf_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594504933,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:netif_napi_add_weight",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594684855,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_schedule_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594866453,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595027829,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595123080,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595203171,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595514444,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595549641,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595585593,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595655667,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596459860,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596968417,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596995081,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597105380,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597266504,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/instrumented-atomic.h:68",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int test_and_set_bit(unsigned int nr, volatile long unsigned int * p)
```

```json
{
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490180416,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "arch/arm64/kernel/debug-monitors.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490190040,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:do_sve_acc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490304648,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "arch/arm64/kernel/perf_event.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx",
        "arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx",
        "arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx",
        "arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490343620,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "arch/arm64/mm/flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/flush.c:__sync_icache_dcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490447884,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490656288,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490674560,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490798000,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490831804,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503927888,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491174048,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491193904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491416052,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491425648,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491703116,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491758640,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492418032,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492478800,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492499048,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492526368,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492570256,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492636712,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:set_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492768832,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492777172,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492887196,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503919120,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493130244,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493166412,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493205676,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493233104,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493592380,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493673948,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493998756,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494033196,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ]
    },
    {
      "addr": 18446603336494687604,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494884960,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495062848,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495115448,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495586088,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495620320,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495795732,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495874648,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495983348,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496054472,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496348120,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511077600,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496716004,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496815156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511111060,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497434740,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498028920,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/dma/amba-pl08x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/amba-pl08x.c:pl08x_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498041536,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/dma/bcm2835-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_callback",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498046260,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_prep_dma_xor",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498055300,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/dma/mv_xor_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_interrupt_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498061624,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/dma/mxs-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mxs-dma.c:mxs_dma_int_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498073596,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498195156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498228740,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498231172,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498386512,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498396808,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498473160,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498492156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498778316,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498827404,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498876904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/iommu/arm-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu.c:arm_smmu_attach_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498888732,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/iommu/arm-smmu-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_bitmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498940860,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499429136,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499455088,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499492232,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499503236,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499542476,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499558496,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499751860,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499886872,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499973816,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500107084,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500215444,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500235332,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500337888,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500563904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500693120,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500844332,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500857032,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500866408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/i2c/i2c-core-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-of.c:of_i2c_register_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501034732,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501135904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501294408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501615164,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/of/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/of/platform.c:of_platform_device_create_pdata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501760320,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501767676,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_alloc_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501795468,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502008332,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502163736,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502284360,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502443984,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502526160,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502749796,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502773744,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502796952,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503173164,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503500108,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/atomic.h:32",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494017344,
      "name": "test_and_set_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282610092,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "arch/powerpc/kernel/pci-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283053600,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "arch/powerpc/platforms/powernv/pci-ioda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_alloc_pe",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_reserve_pe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283279684,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283346572,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "arch/powerpc/kvm/book3s_hv_ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_ras.c:kvmppc_realmode_hmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283466528,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283497800,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283621248,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/workqueue.c:try_to_grab_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283665952,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297775852,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284074384,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284097548,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284364016,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284373924,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284724640,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284800136,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285684632,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285760368,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285782504,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285820464,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285879048,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285954192,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286133888,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286142684,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286285444,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297814080,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286605456,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286659644,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286712404,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286755272,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287162712,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287291320,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287647124,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287669984,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288503568,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288743764,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288954508,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289017008,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289685440,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289741520,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289968456,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290075732,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290208548,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290288036,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290671008,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290789668,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290885924,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291429728,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291570540,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291581140,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291661888,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291682440,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291969156,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292042500,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292078476,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292674772,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292715956,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292773764,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292790704,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292835120,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292847072,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293096152,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293208100,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293315440,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293504904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293526176,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293645108,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293960976,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294128080,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294305788,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294323304,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294328180,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/i2c/i2c-core-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-of.c:of_i2c_register_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294517372,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294632608,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294815924,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295041096,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "drivers/of/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_device_create_pdata"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295425024,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295634420,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295784204,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295992272,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296090488,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296373776,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296408464,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296437420,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296899200,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297281408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297691856,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/powerpc/include/asm/bitops.h:141",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271360282,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "arch/riscv/mm/cacheflush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/cacheflush.c:flush_icache_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270616478,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271412488,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271484946,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271503076,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279796224,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271725174,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271892596,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272079730,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272547408,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272556410,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272580128,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272652632,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:set_wb_congested"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272745794,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272750386,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270890336,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272983780,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273236410,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273299462,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273515684,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273541464,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274044422,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274200622,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274331274,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274369552,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274749480,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274779740,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274931612,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274998096,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275082962,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275130248,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275394544,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275466532,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275523882,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275970992,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276054114,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276059336,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276109722,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276123190,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276272602,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276325624,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276655660,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276677596,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276706060,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276716058,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276744168,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276751918,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276911520,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276988558,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277052374,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277138470,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277154212,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277228430,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277421110,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277550676,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277647798,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277659118,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277661914,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/i2c/i2c-core-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-of.c:of_i2c_register_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277772648,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277845644,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278078182,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "drivers/of/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_device_create_pdata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278287922,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278417610,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278515938,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278632398,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278697754,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278871966,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278895566,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278914754,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279215076,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279468936,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "arch/riscv/include/asm/bitops.h:72",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887563,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941365,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998437,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579029499,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579053023,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099485,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136979,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243374,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491984,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579504629,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579604005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579633830,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589786591,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954474,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006001,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157816,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580163708,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580403836,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580451556,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454322,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581027925,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078371,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092931,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118853,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158165,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209133,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581332231,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338606,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581445463,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773277,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652113,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581687897,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720812,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746198,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022437,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582099070,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366628,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582384217,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582968457,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583139109,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583290107,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333537,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583749631,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583783221,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583934536,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009089,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102203,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584156904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584427039,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584480097,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584534065,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604935696,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584971752,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585294005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585465102,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585470613,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585522424,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585535841,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585744540,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585790102,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585908051,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586230627,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586255680,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586294686,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586304829,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335977,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345141,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461316,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586582493,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586738488,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586843669,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586862529,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586946226,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587132194,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587450435,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587530885,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587649559,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588071683,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588223719,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588325986,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588465717,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588531910,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588738175,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588764644,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588785517,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589112582,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589396217,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665553,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578881163,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938341,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985759,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579031921,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067735,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178958,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420848,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579433493,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532645,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562150,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509135,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892335,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944673,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580103928,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580111324,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351068,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580398628,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580401394,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580974021,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025555,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040115,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065877,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105029,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155885,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581275943,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282318,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581387831,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589496100,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590600,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626953,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659657,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684822,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581960005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036510,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582304324,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321913,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582905609,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583076261,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583227243,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270641,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583686687,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583720277,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583871480,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583944913,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037883,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584092168,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362287,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584418225,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584880552,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585108318,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/nfit/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nfit/core.c:acpi_nfit_ars_rescan",
        "drivers/acpi/nfit/core.c:scrub_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585246517,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585335134,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585340629,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585392248,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585405665,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585603724,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585649286,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586048995,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586074048,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586136062,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586146205,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586177305,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586186469,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586337556,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586451005,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586605704,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586785877,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586803841,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586887394,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587015052,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587218643,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587299045,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587423431,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587556192,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/vmbus_drv.c:vmbus_isr",
        "drivers/hv/vmbus_drv.c:vmbus_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587561510,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/hv/connection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/connection.c:vmbus_on_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587785107,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587936551,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588038226,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177717,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588243910,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588450127,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588476580,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588497453,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588837622,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589121209,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391377,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887499,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941301,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998021,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579029083,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579052607,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099037,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136531,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244446,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491904,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579504549,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601285,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631094,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590229999,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579946010,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997537,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580149288,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155180,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580395084,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580442804,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580445570,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581019125,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069571,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084131,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110053,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149365,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200333,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581323431,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329806,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581436663,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590216685,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643425,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679209,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712124,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737510,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582013717,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089550,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357108,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374697,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957065,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123141,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583274139,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317313,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583733407,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583766981,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583918296,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583992849,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584085963,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584140664,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584409951,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584474833,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529777,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605013152,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584980952,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585482373,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585654478,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585659989,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585711832,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725249,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585933580,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585979142,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586097699,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488115,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586513168,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586552174,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562317,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593465,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586602629,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586778477,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586936040,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587092149,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587111009,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587194706,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587380674,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587504828,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587635092,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587647122,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587775603,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856053,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587980711,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588403459,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588555543,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588657810,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588797893,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588864086,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588936826,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netfilter/nf_conntrack_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588967103,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netfilter/nf_conntrack_proto_udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet",
        "net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588985785,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netfilter/nf_conntrack_proto_gre.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589174351,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200820,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589221693,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589549446,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833081,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590108929,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "test_and_set_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887851,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_add",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941877,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000677,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579032651,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579056543,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:alloc_intr_gate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103456,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141651,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249998,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "arch/x86/kernel/cpu/perfctr-watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi",
        "arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524400,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579537189,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635973,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665110,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590280591,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:__wait_on_bit_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579992444,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044401,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580201270,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_broadcast_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580207196,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450908,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580498436,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501202,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581080434,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131091,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146051,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:set_page_dirty",
        "mm/page-writeback.c:__set_page_dirty_no_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172453,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581212021,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263645,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581387431,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393758,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581501159,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590267048,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709809,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745915,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779657,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581805750,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582084229,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_start_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582162286,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582436724,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582454711,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dquot_add_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045545,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583215413,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583368843,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583412337,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583834159,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_open_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583867973,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584019688,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_test_and_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584095153,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188827,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_schedule_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584244824,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:__blk_req_zone_write_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584516015,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584580961,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584637553,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605034744,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/tables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_os_physical_table_override"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585087128,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585590757,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585762606,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585768101,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585819864,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:setledstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585833281,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:redraw_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586041564,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586086982,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586206307,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586599859,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586624912,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_free_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586664078,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586674605,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586705689,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586714901,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586884525,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_allocate_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034507,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587199365,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587218583,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587301778,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587493954,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587612396,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587746292,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587758402,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587888947,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587971237,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588096087,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588539923,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_stacked_transfer_operstate",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__netif_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588693575,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588798082,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588939509,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589005558,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589214383,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240946,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589261803,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589596902,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589884343,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159240,
      "name": "test_and_set_bit",
      "external": false,
      "loc": "include/asm-generic/bitops-instrumented.h:141",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int test_and_set_bit(unsigned int nr, volatile long unsigned int * p)
```
</details>
</li>
</ul>
