# Function: <code>of_css</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579967024,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup.c:461",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup.c:cgroup_events_show",
        "kernel/cgroup.c:cgroup_pidlist_stop",
        "kernel/cgroup.c:cgroup_release_agent_show",
        "kernel/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup.c:cgroup_controllers_show",
        "kernel/cgroup.c:cgroup_root_controllers_show",
        "kernel/cgroup.c:cgroup_pidlist_next",
        "kernel/cgroup.c:cgroup_pidlist_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_percpu_seq_show",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/cpuset.c:cpuset_common_seq_show",
        "kernel/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-throttle.c:tg_print_max",
        "block/blk-throttle.c:tg_set_conf",
        "block/blk-throttle.c:tg_set_max",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfqg_print_weight_device",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfq_print_weight",
        "block/cfq-iosched.c:cfq_print_leaf_weight",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:__cfqg_set_weight_device",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "net/core/netprio_cgroup.c:read_priomap",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/ipv4/tcp_memcontrol.c:tcp_cgroup_reset",
        "net/ipv4/tcp_memcontrol.c:tcp_cgroup_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967024,
      "name": "of_css",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580003673,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup.c:498",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_pidlist_next",
        "kernel/cgroup.c:cgroup_pidlist_stop",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup.c:cgroup_events_show",
        "kernel/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup.c:cgroup_controllers_show",
        "kernel/cgroup.c:cgroup_release_agent_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_pids.c:pids_events_show",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/cpuset.c:cpuset_common_seq_show",
        "kernel/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_max",
        "block/blk-throttle.c:tg_print_max",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfq_print_leaf_weight",
        "block/cfq-iosched.c:cfq_print_weight",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997536,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580036118,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup.c:501",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_pidlist_next",
        "kernel/cgroup.c:cgroup_pidlist_stop",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup.c:cgroup_events_show",
        "kernel/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup.c:cgroup_controllers_show",
        "kernel/cgroup.c:cgroup_release_agent_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_pids.c:pids_events_show",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/cpuset.c:cpuset_common_seq_show",
        "kernel/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_max",
        "block/blk-throttle.c:tg_print_max",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfq_print_leaf_weight",
        "block/cfq-iosched.c:cfq_print_weight",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028208,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580057815,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:455",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfq_print_leaf_weight",
        "block/cfq-iosched.c:cfq_print_weight",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030240,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580079800,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:558",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/stat.c:cgroup_stat_show_cputime",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfq_print_leaf_weight",
        "block/cfq-iosched.c:cfq_print_weight",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076928,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580137640,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:561",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfq_print_leaf_weight",
        "block/cfq-iosched.c:cfq_print_weight",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135952,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580184744,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183168,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230508,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228560,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580278716,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276768,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580381753,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:623",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:swap_high_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_events_local_show",
        "mm/hugetlb_cgroup.c:hugetlb_events_show",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344928,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580368668,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:620",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:swap_high_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_events_local_show",
        "mm/hugetlb_cgroup.c:hugetlb_events_show",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331152,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580371695,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:620",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_cg_current_show",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/cgroup/misc.c:misc_cg_max_show",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:swap_high_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_events_local_show",
        "mm/hugetlb_cgroup.c:hugetlb_events_show",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334288,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580532099,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:651",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_cg_current_show",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/cgroup/misc.c:misc_cg_max_show",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:swap_high_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_events_local_show",
        "mm/hugetlb_cgroup.c:hugetlb_events_show",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "block/blk-ioprio.c:ioprio_show_prio_policy",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488912,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580729363,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:652",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_events_show",
        "kernel/cgroup/misc.c:misc_cg_current_show",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/cgroup/misc.c:misc_cg_max_show",
        "mm/memcontrol.c:zswap_max_write",
        "mm/memcontrol.c:zswap_max_show",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:swap_high_show",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_events_local_show",
        "mm/hugetlb_cgroup.c:hugetlb_events_show",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "block/blk-ioprio.c:ioprio_show_prio_policy",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683232,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581005075,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:657",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_events_show",
        "kernel/cgroup/misc.c:misc_cg_current_show",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/cgroup/misc.c:misc_cg_max_show",
        "mm/memcontrol.c:zswap_max_write",
        "mm/memcontrol.c:zswap_max_show",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:swap_high_show",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_events_local_show",
        "mm/hugetlb_cgroup.c:hugetlb_events_show",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "block/blk-ioprio.c:ioprio_show_prio_policy",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954832,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581093667,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:656",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_events_show",
        "kernel/cgroup/misc.c:misc_cg_current_show",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/cgroup/misc.c:misc_cg_max_show",
        "mm/memcontrol.c:zswap_max_write",
        "mm/memcontrol.c:zswap_max_show",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:swap_high_show",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_events_local_show",
        "mm/hugetlb_cgroup.c:hugetlb_events_show",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "block/blk-ioprio.c:ioprio_show_prio_policy",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041936,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581191187,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:636",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_local_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_local_stat_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/sched/build_utility.c:cpuacct_all_seq_show",
        "kernel/sched/build_utility.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_events_show",
        "kernel/cgroup/misc.c:misc_cg_current_show",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/cgroup/misc.c:misc_cg_max_show",
        "mm/memcontrol.c:zswap_writeback_write",
        "mm/memcontrol.c:zswap_writeback_show",
        "mm/memcontrol.c:zswap_max_write",
        "mm/memcontrol.c:zswap_max_show",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:swap_high_show",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_events_local_show",
        "mm/hugetlb_cgroup.c:hugetlb_events_show",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-ioprio.c:ioprio_set_prio_policy",
        "block/blk-ioprio.c:ioprio_show_prio_policy",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139152,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491525880,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491523640,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225528708,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225490240,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284491704,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284488272,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271945790,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271943092,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247516,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245568,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580195068,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193120,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580238764,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236816,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * of_css(struct kernfs_open_file * of)
```

```json
{
  "name": "of_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580291756,
      "name": "of_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_seqfile_show",
        "kernel/cgroup/cgroup.c:cgroup_freeze_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_events_show",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_show",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_show",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_cfs_stat_show",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show",
        "kernel/sched/cpuacct.c:cpuacct_stats_show",
        "kernel/sched/cpuacct.c:cpuacct_all_seq_show",
        "kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/pids.c:pids_events_show",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_read",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_show",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/slab_common.c:memcg_slab_show",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:memcg_slab_start",
        "mm/memcontrol.c:swap_events_show",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_max_show",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_oom_group_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_events_local_show",
        "mm/memcontrol.c:memory_events_show",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_show",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_high_show",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_low_show",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memory_min_show",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_oom_control_read",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_reset",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_seq_show",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_set_limit",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_show",
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netprio_cgroup.c:read_priomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289808,
      "name": "of_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
