# Function: <code>arch_atomic64_add</code>

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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579414631,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579580810,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579641566,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579644982,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646406,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579705272,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710761,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579726122,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579750832,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265267,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580170420,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580184265,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200223,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580457115,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580636022,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817427,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580851036,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580876861,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936730,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580946039,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580986056,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013847,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581036908,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045073,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068664,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095901,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134398,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198915,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230424,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581242054,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299571,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369166,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429203,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451450,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581459125,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493049,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524677,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605556,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581777931,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944015,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965782,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582405660,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463693,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560651,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583537869,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583581986,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_queue_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583624975,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583725723,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771474,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583873037,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583913419,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585839563,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586607184,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587190054,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588189934,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588516883,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588874933,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579449101,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579618442,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579679186,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682534,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683974,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744540,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579748552,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579768438,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579790864,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509520,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable",
        "kernel/locking/rwsem-xadd.c:__rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218317,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580232265,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249569,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512587,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884099,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919499,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951497,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968632,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:memblock_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004282,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022188,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581063112,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087545,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114492,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122465,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146456,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175103,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210830,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282263,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604790884,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313403,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326227,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383141,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458010,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501062,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535068,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542821,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581578921,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613045,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690979,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581863716,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029702,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047284,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582504924,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563010,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582659583,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531422,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583692607,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:generic_make_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730085,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839415,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843942,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958339,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583997995,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974124,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586269063,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586756048,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587369990,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588373702,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588712448,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589097971,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579642486,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579712068,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716377,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717735,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579750991,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579777129,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795757,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818656,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862717,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580267024,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580283033,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580305182,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570538,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912843,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580981326,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179164,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187142,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213512,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286989,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378209,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581386344,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604893747,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423958,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445610,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494500,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581572269,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580290,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610692,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638287,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581651829,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688496,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724685,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740377,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808950,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581988422,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169459,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582675857,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738203,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834850,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719535,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583881231,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583916924,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583946358,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584029623,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034349,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138472,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584181453,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218487,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586513092,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587011552,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641317,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588774737,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589131423,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589552976,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579668454,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579754263,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579758809,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760166,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793023,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824799,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579841788,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579866751,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911429,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315342,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580331257,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580353901,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617690,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966548,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035454,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237276,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245685,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272024,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345709,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439411,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581447288,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604927652,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485350,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509834,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559012,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637485,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645315,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681604,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720550,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724357,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761810,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581798253,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581813681,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581881542,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582074206,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246851,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582777889,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840379,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582939989,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828415,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583984383,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584020211,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584049926,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133527,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138189,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584151855,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584260920,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584315149,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366535,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586661044,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587211040,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587845429,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588998337,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589355555,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589777008,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579699673,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579788513,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792313,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793782,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818349,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864216,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880423,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907983,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579955120,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580386865,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580403610,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580424372,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_root_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717978,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922845,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128174,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207609,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426060,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434580,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462072,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493737,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542061,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581647875,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652504,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609241878,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707676,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769268,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:region_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835032,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581860723,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581904666,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942176,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981032,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__mod_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021382,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033659,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582310515,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483615,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582517333,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_file_get",
        "fs/io_uring.c:__io_async_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583089489,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142652,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583239170,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584223715,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445862,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530689,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584537175,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584549423,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584668248,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584726944,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134471,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587458076,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588063552,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588686293,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588780688,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_make_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589957846,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590336310,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590796777,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579678151,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579780012,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783161,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784806,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579809693,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579856555,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873527,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579901615,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943593,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580373983,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390986,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580411842,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_root_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580707418,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919101,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084497,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581162282,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250026,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469332,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581477494,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535289,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585300,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694349,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581700121,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612308295,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755420,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817457,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:region_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880906,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905651,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581959553,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989520,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582031250,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__mod_memcg_lruvec_state",
        "mm/memcontrol.c:memcg_reparent_objcgs",
        "mm/memcontrol.c:memcg_reparent_objcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582065721,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081372,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363441,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582540204,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560321,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_buffer_account_pin",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_sqe_files_unregister",
        "fs/io_uring.c:io_file_get",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:io_async_buf_func",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583168547,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224757,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340998,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584342579,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584562112,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635534,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584644988,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584661087,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786142,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584840145,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587220208,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587526269,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588108880,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588713506,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589998662,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590388982,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590856025,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579684612,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579788139,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579791273,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792934,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579817606,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865083,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882239,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910687,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579951342,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580376910,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580393895,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580411860,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580711498,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923005,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102993,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179258,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258406,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334162,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428060,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581490068,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498267,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557401,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607543,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:finish_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717408,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581721833,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614448445,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753203,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782972,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581845365,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:region_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912602,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581985396,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582017331,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582057982,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_flush_lruvec_page_state",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090260,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106584,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582391089,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582569212,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582587010,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_buffer_account_pin",
        "fs/io_uring.c:io_file_get",
        "fs/io_uring.c:io_prep_rw",
        "fs/io_uring.c:tctx_task_work"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583195389,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252602,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363910,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584377326,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595024,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584662622,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584673228,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584689423,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830206,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584884804,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587108544,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587407933,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587991456,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588598706,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589912662,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590305283,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590784952,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579761010,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579883604,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886972,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888823,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919251,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976947,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997903,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580029729,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580078066,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580538148,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580555975,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574964,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580889770,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125565,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332625,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418829,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494966,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582338,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679980,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748486,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758269,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821481,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874663,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:finish_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989568,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581994039,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615391582,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034291,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582066506,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582136621,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208042,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582287473,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319971,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582365966,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402844,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422736,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582696074,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582886492,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906251,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_buffer_account_pin",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:__io_splice_prep",
        "fs/io_uring.c:io_prep_rw",
        "fs/io_uring.c:tctx_task_work",
        "fs/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583538426,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595209,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583706823,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584771998,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009707,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585077902,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585091116,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585111645,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585248926,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310647,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587692081,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587979980,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588604512,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589275586,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590679110,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591092659,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591602792,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579868400,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580000874,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580029659,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580115301,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:account_system_index_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_user_time",
        "kernel/sched/build_policy.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580172371,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:put_prev_task_stop",
        "kernel/sched/build_utility.c:calc_global_load_tick",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580214006,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580735587,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580755087,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580776839,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581124794,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396701,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637590,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748155,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841438,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582056737,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582130742,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:fold_vm_numa_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582137241,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212441,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272883,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411652,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417128,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617181813,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463329,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582503642,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582586019,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700657,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:init_kmem_cache_nodes",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582771225,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582812179,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582863801,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:__refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918635,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582939121,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245129,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454322,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584071389,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134076,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584260939,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585456382,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585675838,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_requests_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725475,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811713,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585819191,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585841405,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585977514,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_buffer_account_pin",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_issue_sqe",
        "io_uring/io_uring.c:io_async_cancel",
        "io_uring/io_uring.c:io_splice",
        "io_uring/io_uring.c:io_tee",
        "io_uring/io_uring.c:io_prep_rw",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:handle_prev_tw_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586090680,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586167841,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589029872,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589337135,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590753921,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592306896,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592743670,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593295711,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011056,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580162514,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199068,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580288837,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:account_system_index_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_user_time",
        "kernel/sched/build_policy.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351798,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:put_prev_task_stop",
        "kernel/sched/build_utility.c:calc_global_load_tick",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406390,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011715,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058687,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434922,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746909,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943030,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_ancestor",
        "kernel/bpf/helpers.c:bpf_cgroup_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582026614,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143810,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582163104,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268133,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582529343,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582606246,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:fold_vm_numa_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614535,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700505,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764963,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918947,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925112,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627874138,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582977233,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583016794,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098060,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202376,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305879,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583354627,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583411226,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:__refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583472950,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495180,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837601,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:wb_io_lists_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044207,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584704067,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584768061,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584910571,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586215294,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586452414,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_requests_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586506724,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593837,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blk_cgroup_bio_start",
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586601296,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586622253,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586766657,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/io_uring.c:handle_tw_list",
        "io_uring/io_uring.c:__io_alloc_req_refill",
        "io_uring/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "io_uring/uring_cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "io_uring/net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586843314,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_account_pin",
        "io_uring/rsrc.c:io_rsrc_refs_refill"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587073912,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587162305,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588396879,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590558208,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590903423,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592431697,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593124739,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594143351,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594351371,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594614950,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594699817,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595199697,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595280994,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580064704,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580210821,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272156,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580356203,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:account_system_index_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_user_time",
        "kernel/sched/build_policy.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580411590,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:put_prev_task_stop",
        "kernel/sched/build_utility.c:calc_global_load_tick",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580475174,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100275,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149807,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531754,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906653,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582218902,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582340989,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360032,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468971,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732621,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582814710,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:fold_vm_numa_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823303,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582914505,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981350,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134960,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141512,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619638691,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583189009,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583225498,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583262749,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583307947,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420864,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583525209,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583573955,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583631482,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:__refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583684514,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710166,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584048059,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:wb_io_lists_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584268872,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584927877,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991405,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585139372,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586394441,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586455207,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/aead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586455982,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/geniv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/geniv.c:aead_init_geniv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586459639,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586468178,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586473994,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_digest",
        "crypto/shash.c:crypto_shash_finup",
        "crypto/shash.c:crypto_shash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478163,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/akcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/akcipher.c:crypto_akcipher_sync_decrypt",
        "crypto/akcipher.c:crypto_akcipher_sync_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586483008,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586490375,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586525347,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586550727,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586722220,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:__blk_mq_alloc_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851665,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859536,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586880525,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587008762,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_activate_pollwq",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:__io_alloc_req_refill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587110147,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_account_pin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587306539,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587332488,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587425403,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588672866,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590886656,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591247570,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592863961,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_account_bio",
        "drivers/md/md.c:md_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593577471,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594530484,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594618493,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594739290,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594754336,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595006914,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595091753,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595595435,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595601372,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595676786,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579963220,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107264,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580149094,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580259387,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313498,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:switched_from_fair",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:rq_offline_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:update_curr_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580425655,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:account_system_index_time",
        "kernel/sched/build_policy.c:account_guest_time",
        "kernel/sched/build_policy.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580510056,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_global_load_tick",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580534998,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580824252,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197699,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254127,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643818,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582030893,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add",
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374102,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461904,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507261,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526864,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637723,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582723038,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582927937,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/shrinker.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shrinker.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582989190,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_node_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__dec_zone_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_node_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__inc_zone_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:fold_vm_numa_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997393,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583015341,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583088393,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156694,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318016,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583324632,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621942691,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583372865,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583398080,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:__memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583461914,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583501136,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:__zswap_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546162,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719871,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583767363,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583826263,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_replace_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:get_obj_cgroup_from_folio",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:__refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583879016,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583910518,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583966883,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:init_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584262907,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:wb_io_lists_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584321497,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584485672,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585142627,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585223053,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_update_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585372156,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_flex_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585967395,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971897,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585975954,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586411332,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_dup_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586453901,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721159,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/aead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721934,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/geniv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/geniv.c:aead_init_geniv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586725282,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/lskcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/lskcipher.c:crypto_lskcipher_decrypt",
        "crypto/lskcipher.c:crypto_lskcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586730823,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586741883,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586744758,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_digest",
        "crypto/shash.c:crypto_shash_finup",
        "crypto/shash.c:crypto_shash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586748099,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/akcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/akcipher.c:crypto_akcipher_sync_decrypt",
        "crypto/akcipher.c:crypto_akcipher_sync_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586752992,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586759623,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586820807,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586999513,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:__blk_mq_alloc_requests_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128977,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587136992,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587158477,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327742,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_activate_pollwq",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:__io_alloc_req_refill",
        "io_uring/io_uring.c:io_prep_async_work",
        "io_uring/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587365343,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587389612,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_account_pin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587412894,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "io_uring/register.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/register.c:__io_uring_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587615880,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587760187,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973503,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591230767,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591594828,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592166125,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/gpu/drm/drm_vblank.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_vblank.c:store_vblank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592793051,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593613981,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_account_bio",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_flush_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594349951,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595333220,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595544810,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595819586,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595904468,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596130534,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596438299,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596524604,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:23",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void arch_atomic64_add(long int i, atomic64_t * v)
```

```json
{
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490447264,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490633004,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490766632,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490846500,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490932540,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490937396,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490938180,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490966568,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491009216,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491030280,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491065392,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491113908,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491301632,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:kcmp_epoll_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491542772,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491593380,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491611212,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491685440,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491831312,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_read_page",
        "kernel/trace/ring_buffer.c:ring_buffer_read_page",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491920384,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492144596,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492314992,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492378948,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:task_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:perf_swevent_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ]
    },
    {
      "addr": 18446603336492394552,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492406740,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492460304,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492480568,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492567364,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492593688,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492632500,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492644580,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492677284,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492713152,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492713568,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/prfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/prfile.c:vma_do_get_file",
        "mm/prfile.c:vma_do_get_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492751412,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492794020,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__arm64_sys_remap_file_pages",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492805980,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__arm64_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492819080,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492843188,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492857708,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492897960,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    },
    {
      "addr": 18446603336492900744,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492933348,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:get_swap_page_of_type",
        "mm/swapfile.c:get_swap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492988364,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493086264,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ]
    },
    {
      "addr": 18446603336493096600,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493111476,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493129132,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493169708,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493173280,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493194556,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ]
    },
    {
      "addr": 18446603336493237680,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493259036,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_isolate",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493269424,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493352524,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493440592,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:__pollwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493483756,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493509108,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:do_dup2",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:dup_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493605776,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493733012,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_detach_connector_from_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493767472,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493817632,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493841480,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494116768,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494444180,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494514264,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494613792,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495040252,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495586540,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495597604,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495638924,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495809412,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495826940,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495856404,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495886856,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495901436,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inc_in_flight",
        "block/genhd.c:part_inc_in_flight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495983484,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495990360,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496011652,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496142044,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496204284,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498357620,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498860260,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_domain_flush",
        "drivers/iommu/iova.c:iova_domain_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499220340,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499484380,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499561292,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500298520,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501078588,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501144840,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501760736,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:pmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501768416,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501776392,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:armpmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501782060,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/perf/hisilicon/hisi_uncore_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501792392,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501798600,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/perf/qcom_l3_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501805260,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/xgene_pmu.c:xgene_perf_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501943932,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_fp_dup",
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502027368,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_forward_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502220084,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502414416,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro_cells.c:gro_cells_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502435624,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:scm_detach_fds_compat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502605980,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502890432,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_out_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502996932,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503191184,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503201112,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_create1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503216052,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/unix/garbage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/garbage.c:inc_inflight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503248748,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503397148,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503421776,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503446336,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503460140,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503481796,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503500172,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503502228,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503624144,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:67",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492339368,
      "name": "arch_atomic64_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336492897960,
      "name": "arch_atomic64_add.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446603336493058608,
      "name": "arch_atomic64_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336493189272,
      "name": "arch_atomic64_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579644774,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579730183,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734729,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579736086,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579768879,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579798568,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579814140,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579839103,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579883541,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580284142,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580300057,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322701,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586490,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580935348,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004302,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206124,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214533,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240872,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314557,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408259,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581416136,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604833112,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454198,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478570,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527748,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606221,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581614051,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650340,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689286,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581693093,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730546,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766989,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782417,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850278,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582042942,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215587,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582746625,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809115,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582908725,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797151,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583953119,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988947,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584018662,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102263,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106925,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120591,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229656,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584283885,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586128423,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586351524,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586917120,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587476405,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588604721,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588961731,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589381376,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579573158,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579659025,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663561,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664886,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579699471,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731551,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579748764,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579773839,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818505,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985664,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580231550,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580247401,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580269981,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580533114,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580881412,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950456,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152876,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581161237,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187538,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258116,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350771,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581358648,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604802173,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396128,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419978,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469406,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547565,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555379,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589101,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628316,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632117,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669292,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705613,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720577,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787942,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581980510,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152473,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582683793,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582746267,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582845877,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583734207,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890047,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583924803,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583954470,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037943,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584042605,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056255,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164856,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584219085,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973031,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586192852,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586858288,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244581,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588316705,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588673667,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589106368,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579642038,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579715831,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719177,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579720534,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753391,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785167,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579802156,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827119,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871701,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580275390,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291305,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313949,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580577738,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580926596,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995502,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197324,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581205733,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232072,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305757,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399459,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581407336,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604910296,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445398,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469882,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581519060,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597533,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605363,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641652,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680598,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684405,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721858,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758301,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773729,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841590,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582034222,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582206067,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582736481,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797995,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897326,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583780911,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583936879,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583972707,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002422,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584086023,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584090685,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584104351,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584213416,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584266797,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586314503,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586609012,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587165600,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587801573,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588928968,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/netfilter/nf_conntrack_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_core.c:nf_ct_kill_acct",
        "net/netfilter/nf_conntrack_core.c:__nf_ct_refresh_acct",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589040897,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589398115,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589818240,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589923639,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/netfilter/nf_conntrack_reasm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue"
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
  "name": "arch_atomic64_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579676391,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579761905,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579766457,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767894,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801231,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826920,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579847132,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872255,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917207,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580329104,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580345657,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_cancel_attach",
        "kernel/cgroup/pids.c:pids_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368878,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634474,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_update_sum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987102,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056661,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260604,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581269010,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581295611,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369757,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463449,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581471432,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:adjust_managed_page_count",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604931833,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509877,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534438,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:swap_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584034,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663389,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671347,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:generic_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708036,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747362,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581751285,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789963,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821981,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842678,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911145,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582105687,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582281030,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582821870,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884852,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582984398,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583881903,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584038788,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076487,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584104840,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188887,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192945,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584208207,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584318040,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584372670,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426204,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721457,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587272672,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587925411,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589080049,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589441203,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589868960,
      "name": "arch_atomic64_add",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:44",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
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
void arch_atomic64_add(long int i, atomic64_t * v)
```
</details>
</li>
</ul>
