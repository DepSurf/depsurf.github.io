# Function: <code>__next_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595003040,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595064441,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595066409,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_set_distance",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595070258,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466160,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595089108,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581853,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:show_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579705088,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:snapshot_write_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005062,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580488054,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580491762,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552410,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:kswapd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580599094,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648201,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580652635,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_destroy",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_drain_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580735220,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580785414,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:next_node_allowed",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_show_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580810278,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580867652,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915636,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958942,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:alloc_migrate_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581089651,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215802,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:free_more_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433071,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494561,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609352,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595247578,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595276045,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584481885,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:257",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595166640,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595230143,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595234711,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:numa_set_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595235970,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595249971,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595256707,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641815,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579726170,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580572370,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595298543,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595302249,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580700902,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595312058,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580759899,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_destroy",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854207,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580915884,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595319532,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995828,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595326813,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255397,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380419,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:free_more_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581614159,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679354,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252145,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583932476,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595429207,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584513544,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:rand_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595459283,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584827677,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595409230,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595473193,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595477759,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595479139,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500138,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595501314,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666524,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753697,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826686,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580638944,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595546511,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580708328,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766710,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595550952,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:setup_vmstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595560373,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580825101,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_destroy",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922414,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580983734,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595567741,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069652,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140904,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333194,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458556,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:free_more_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702924,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581767566,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367473,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584073985,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595681487,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584695610,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:rand_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595712554,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020866,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596328555,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596394754,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596399307,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596400581,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579489952,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642507,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579680339,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749934,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826549,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580670431,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596471287,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580743047,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580803158,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596476795,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596487140,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580867366,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966781,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581030074,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596495063,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120216,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188083,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388577,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514752,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:free_more_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756799,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581820894,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584140436,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596605808,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584777378,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:rand_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596637444,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585106058,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216545,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:259",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602646669,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602713423,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602718978,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602720255,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516224,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579673211,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715158,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783257,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862364,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580755452,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602798103,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830007,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891862,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602803634,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602813961,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958598,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068445,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602818698,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139581,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602822301,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232613,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317203,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528769,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581903103,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581970478,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584414715,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602936165,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585197490,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:rand_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602967532,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585532106,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766513,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602816683,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602886087,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602891783,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602893139,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602912472,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579705915,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746870,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579815160,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579895766,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580891045,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602971386,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602976213,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027845,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602976904,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602987263,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092694,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206891,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602992124,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284075,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602995849,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368833,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603003546,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689957,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088694,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582156315,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584638137,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603109196,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432879,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603138929,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585775787,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589145328,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604611719,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604683097,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604689141,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604690497,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604710080,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579745195,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786864,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861912,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942801,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580964685,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604771355,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776190,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105381,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776881,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604787364,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581170374,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291099,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604791246,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:_enable_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581365803,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794971,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457696,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604802087,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_nr_lru_pages",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776864,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582182358,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251120,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584737225,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604911921,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585556986,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604943359,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585909323,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380464,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604707279,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604782575,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604788931,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604790286,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810396,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579773733,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579814613,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896151,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981520,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058325,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604871560,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581170213,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604872211,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604883100,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241410,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581365002,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604890375,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604894091,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479046,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604897879,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571951,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604905384,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581895320,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344772,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582415714,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584939209,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605020714,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777509,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605051184,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586148987,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837520,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604719666,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604785847,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604808342,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604814621,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604815986,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604835288,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579630261,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579816405,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862389,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579946423,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580031184,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114085,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604905478,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228245,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604906117,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604917035,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299858,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424505,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604924312,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604927996,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581543334,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604931819,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637167,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604939343,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967928,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582443635,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514658,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585075001,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605057665,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585920213,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605088152,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586297499,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063664,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609066463,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609128989,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609147059,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609151196,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609154528,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609171579,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609178194,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579857129,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:numa_group_count_active_nodes",
        "kernel/sched/fair.c:numa_group_count_active_nodes",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579903400,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991849,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083140,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/irq/affinity.c:get_nodes_in_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292621,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609223576,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416141,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609224378,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609231280,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581489734,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626025,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609238401,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609242186,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753069,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609246694,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581853186,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:init_kmem_cache_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609252655,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_alloc_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_one_shrinker_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201559,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582556360,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_all",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737573,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818938,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585060560,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609347001,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586658253,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609375052,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587067739,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612129830,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612196298,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612217396,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612224073,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612224983,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612243628,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579849481,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:numa_group_count_active_nodes",
        "kernel/sched/fair.c:numa_group_count_active_nodes",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898312,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976553,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065716,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/irq/affinity.c:get_nodes_in_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336781,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612290705,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581459261,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612291474,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612298412,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531398,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681401,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612304796,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612308603,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806963,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:allowed_mems_nr",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612313049,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901218,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:init_kmem_cache_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612318964,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_alloc_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_one_shrinker_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582249031,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582625872,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_cpu_online",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808613,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582891834,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585209856,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612418092,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586768781,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612446312,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587152316,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int __next_node(int n, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614269743,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591205083,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071614358619,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591215704,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ]
    },
    {
      "addr": 18446744071614365821,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646832,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init"
      ]
    },
    {
      "addr": 18446744071579857884,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907315,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579978667,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065644,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356485,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614430561,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480093,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614431122,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532689,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_init"
      ]
    },
    {
      "addr": 18446744071581553761,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706384,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725881,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:page_alloc_init_late"
      ]
    },
    {
      "addr": 18446744071581784706,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": [
        "mm/swapfile.c:swapfile_init"
      ]
    },
    {
      "addr": 18446744071581834930,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581855407,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071581933571,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_init"
      ]
    },
    {
      "addr": 18446744071582024083,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_lruvec_page_state",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_init"
      ]
    },
    {
      "addr": 18446744071582274735,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655190,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_cpu_online",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_exit_workers",
        "fs/io-wq.c:io_wq_exit_workers",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838123,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582920404,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585092832,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614558931,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586648051,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614586876,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587040938,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591205083,
      "name": "__next_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071591215704,
      "name": "__next_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071591223101,
      "name": "__next_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071581532544,
      "name": "__next_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581723088,
      "name": "__next_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581780752,
      "name": "__next_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071581854320,
      "name": "__next_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071591276897,
      "name": "__next_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071582019472,
      "name": "__next_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615191917,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615268126,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615289065,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615296170,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615297222,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615317403,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965772,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025640,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580110104,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199116,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604338,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615370455,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734557,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615371044,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615379315,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817249,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978256,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615387698,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615391956,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124720,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615397339,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582232505,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245633,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/migrate.c:__disable_all_migrate_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615404241,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593215,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987255,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_max_workers",
        "fs/io-wq.c:io_wq_cpu_affinity",
        "fs/io-wq.c:__io_wq_cpu_online",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_cancel_cb",
        "fs/io-wq.c:io_wq_cancel_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170841,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255012,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585540432,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615513131,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587195718,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615543301,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587608650,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617044046,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617068412,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617076019,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617077083,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617099420,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081101,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199285,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580250037,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352258,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964506,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617158408,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115647,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617159037,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617168132,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208822,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_init_list_lru_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582386292,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:show_numa_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617177561,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617182242,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570381,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617189260,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700350,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:init_kmem_cache_nodes",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716355,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/migrate.c:__disable_all_migrate_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617196290,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872647,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123423,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583662212,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583755067,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586037623,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_max_workers",
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:__io_wq_cpu_online",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:io_wq_cancel_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695120,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617317194,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617349014,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617358556,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:node_read_distance"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579382859,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450279,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627684721,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627717050,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627729117,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627730064,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627760898,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252621,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390129,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450024,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574562,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068487,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397602,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627843033,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_del_mm",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582589495,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627843703,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627855352,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582695411,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_init_list_lru_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582891396,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:show_numa_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627868700,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627874759,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627881064,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627884933,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583226668,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627893167,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memory_tier_init",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583334006,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627894877,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583418222,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583694015,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584267773,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584371153,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586873479,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_max_workers",
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:__io_wq_cpu_online",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:io_wq_cancel_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628039941,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628083935,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628096367,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:node_read_distance"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579392251,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462455,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619442624,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619474522,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619488317,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619489284,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619521730,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318237,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458722,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520056,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158845,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582603506,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619607529,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_release_memcg",
        "mm/vmscan.c:lru_gen_offline_memcg",
        "mm/vmscan.c:lru_gen_online_memcg",
        "mm/vmscan.c:lru_gen_del_mm",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:reparent_shrinker_deferred",
        "mm/vmscan.c:alloc_shrinker_info",
        "mm/vmscan.c:free_shrinker_info",
        "mm/vmscan.c:expand_one_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796855,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619608199,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619620852,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:page_alloc_init_late",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619631784,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582902212,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/show_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/show_mem.c:__show_free_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909331,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_init_list_lru_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583106596,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:show_numa_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181495,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619639223,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619644232,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619648165,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node",
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445436,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619656095,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memory_tier_init",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553574,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619657796,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583638489,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583911903,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584498030,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584599473,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588179349,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619805430,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619850019,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619862287,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:node_read_distance"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579420893,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579492519,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621738760,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621771002,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621784669,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621786100,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370973,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518370,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580581380,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264349,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774962,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621911657,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_release_memcg",
        "mm/vmscan.c:lru_gen_offline_memcg",
        "mm/vmscan.c:lru_gen_online_memcg",
        "mm/vmscan.c:lru_gen_del_mm",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582927980,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/shrinker.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shrinker.c:reparent_shrinker_deferred",
        "mm/shrinker.c:expand_one_shrinker_info",
        "mm/shrinker.c:alloc_shrinker_info",
        "mm/shrinker.c:free_shrinker_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582971479,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621912375,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621924996,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:page_alloc_init_late",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621935832,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073716,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/show_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/show_mem.c:show_free_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082227,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_init_list_lru_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583289220,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:show_numa_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583365287,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583429644,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621945415,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494652,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:shrink_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621951704,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:remove_pool_hugetlb_folio",
        "mm/hugetlb.c:alloc_pool_huge_folio",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621955173,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:interleave_nid",
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621961168,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memory_tier_init",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583742966,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621963854,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:__invalidate_reclaim_iterators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833577,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584117727,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584722914,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584831185,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588470197,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622096596,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622113899,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622158851,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622170847,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:270",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:node_read_distance"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510815880,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/setup.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510836664,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/arm64/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510877604,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490997880,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491060120,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491236224,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492482452,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336510943696,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492618768,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510944472,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510955112,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492707624,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492826536,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510963072,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510967780,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492975172,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510971832,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493086004,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510979324,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493471472,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494056512,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494144096,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497478348,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511199400,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498741260,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499130520,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503840912,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236460000,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302445920,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:initmem_init",
        "arch/powerpc/mm/numa.c:mem_topology_setup",
        "arch/powerpc/mm/numa.c:dump_numa_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283079940,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/powerpc/platforms/powernv/opal-imc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283084192,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/powerpc/platforms/powernv/memtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283398160,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283625936,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283869744,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283938580,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284136092,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285768104,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302591752,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285936188,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302592776,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302606212,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286044132,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286210528,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302616340,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302621584,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286395260,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302626484,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286532904,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302637476,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287030248,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287712592,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287820784,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291902220,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292321016,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297692312,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279731684,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604645956,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604722284,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604728563,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729928,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606565,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792181,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579834741,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914199,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999920,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082933,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604810938,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197093,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811577,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822495,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268706,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393353,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604829772,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604833456,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512070,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604837279,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605903,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604844803,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936664,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412371,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483394,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585004489,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604957383,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585681189,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604987765,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586060747,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586486491,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/nvme/host/multipath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665920,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604613890,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604690186,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604696293,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604697658,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535205,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722965,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769317,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853431,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938592,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030117,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604779999,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143845,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604780638,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604791556,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215362,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335929,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604798833,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604802517,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454262,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604806340,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547247,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604813864,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874248,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350067,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420626,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584920073,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585541061,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604952076,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585906699,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586362571,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/nvme/host/multipath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391744,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604723748,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604799851,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604806130,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604807495,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603845,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776773,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579822757,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906695,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991456,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074133,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604888122,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188293,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604888761,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604899679,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259906,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384553,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604906956,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604910640,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581503382,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604914463,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597215,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604921987,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927976,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402851,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582473874,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585026585,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605037988,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585870613,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605068475,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586246395,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590109296,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
  "name": "__next_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604723778,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604789988,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812470,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818749,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_alloc_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820114,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/mm/amdtopology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/amdtopology.c:amd_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604839445,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579639450,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_pool_ids_show",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824877,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:show_numa_stats",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start",
        "kernel/sched/fair.c:task_scan_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579867877,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952759,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580038192,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135861,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604909659,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd_init",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251621,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mmzone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_online_pgdat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604910298,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604921216,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_init",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:sysctl_compaction_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324610,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:__list_lru_init",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448873,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604928493,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:page_alloc_init_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604932177,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapfile_init",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:setup_swap_info",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:__del_from_avail_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568289,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604935990,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:offset_il_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663071,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604943514,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581998056,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_sb",
        "fs/dcache.c:shrink_dcache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483267,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:show_numa_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582554434,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kcore_update_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585132745,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605061845,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585978517,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605092346,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586356411,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159632,
      "name": "__next_node",
      "external": false,
      "loc": "include/linux/nodemask.h:269",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:__next_node_in"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int __next_node(int n, const nodemask_t * srcp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int __next_node(int n, const nodemask_t * srcp)
```
</details>
</li>
</ul>
