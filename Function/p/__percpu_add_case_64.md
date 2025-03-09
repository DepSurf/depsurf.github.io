# Function: <code>__percpu_add_case_64</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __percpu_add_case_64(void * ptr, long unsigned int val)
```

```json
{
  "name": "__percpu_add_case_64",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490846376,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491245872,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__srcu_read_unlock",
        "kernel/rcu/srcutree.c:__srcu_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491568512,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491583664,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491591556,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491596724,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge",
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491616892,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492234968,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492318484,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492367036,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492459808,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492481640,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492500240,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492520240,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_cache_add_active_or_unevictable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492570868,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492596004,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492628852,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vm_events_fold_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492643656,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492676988,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492699516,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492721904,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492753700,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492768012,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492799248,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492875140,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:__alloc_pages_direct_compact"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492911132,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492918004,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493015436,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:change_prot_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493065740,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117776,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493147588,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493156240,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_alloc_page",
        "mm/khugepaged.c:khugepaged_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493196096,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:percpu_ref_put_many",
        "mm/memcontrol.c:percpu_ref_tryget_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493225736,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493283468,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493459220,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_instantiate",
        "fs/dcache.c:__d_alloc",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_lru_shrink_move",
        "fs/dcache.c:d_shrink_add",
        "fs/dcache.c:d_shrink_del",
        "fs/dcache.c:d_lru_del",
        "fs/dcache.c:d_lru_del",
        "fs/dcache.c:d_lru_add",
        "fs/dcache.c:d_lru_add",
        "fs/dcache.c:dentry_unlink_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493494244,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_list_add",
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:inode_init_always"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493607588,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493666956,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493700088,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493731648,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493810964,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__arm64_sys_io_cancel",
        "fs/aio.c:__arm64_compat_sys_io_submit",
        "fs/aio.c:__arm64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__arm64_sys_io_destroy",
        "fs/aio.c:__arm64_compat_sys_io_setup",
        "fs/aio.c:__arm64_sys_io_setup",
        "fs/aio.c:lookup_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493849244,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493867816,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493994356,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/drop_caches.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495773108,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495809256,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495838892,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495855244,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495875916,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495886600,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495982712,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495995368,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued",
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496011464,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496141912,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499220268,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499561068,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501078668,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502113740,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup",
        "net/core/neighbour.c:neigh_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502223212,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502608828,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502630156,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_skb",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502695904,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502715648,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_newly_delivered",
        "net/ipv4/tcp_input.c:tcp_newly_delivered",
        "net/ipv4/tcp_input.c:tcp_oow_rate_limited",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_input.c:tcp_check_reno_reordering",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    },
    {
      "addr": 18446603336502759204,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    },
    {
      "addr": 18446603336502793124,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502805252,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502821296,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502822476,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_mark_skb_lost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502829192,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502836556,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502860144,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ]
    },
    {
      "addr": 18446603336502890032,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_out_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502920148,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503003676,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503054276,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503078776,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503136024,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503176876,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503183280,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503190944,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503233672,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_send_skb",
        "net/ipv6/ip6_output.c:ip6_send_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    },
    {
      "addr": 18446603336503336716,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503401496,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503416176,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503434428,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503443712,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503459428,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503495360,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503502264,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503537112,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish",
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish",
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish",
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503562368,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503568440,
      "name": "__percpu_add_case_64",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502700448,
      "name": "__percpu_add_case_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336502744360,
      "name": "__percpu_add_case_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336502840384,
      "name": "__percpu_add_case_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336503230608,
      "name": "__percpu_add_case_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __percpu_add_case_64(void * ptr, long unsigned int val)
```
</details>
</li>
</ul>
