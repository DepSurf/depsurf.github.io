# Function: <code>strim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582982416,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:454",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_feat_write",
        "kernel/cgroup.c:cgroup_release_agent_write",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:__elevator_change",
        "block/cfq-iosched.c:__cfqg_set_weight_device",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:policy_store",
        "net/ipv4/tcp_memcontrol.c:tcp_cgroup_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982416,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583271600,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:454",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_release_agent_write",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:__elevator_change",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:policy_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271600,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583390368,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:454",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_release_agent_write",
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:__elevator_change",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390368,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588246400,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:454",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246400,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588797824,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:455",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797824,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589175920,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:455",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175920,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589405840,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:456",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405840,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589861728,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:498",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861728,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590087520,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590087520,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585085520,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:541",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:blk_trace_str2mask",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:__list_lookup_parent",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:__elevator_change",
        "block/blk-mq-debugfs.c:queue_state_write",
        "lib/bootconfig.c:xbc_parse_key",
        "lib/bootconfig.c:__xbc_parse_keys",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085520,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585234656,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:538",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:blk_trace_str2mask",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:__list_lookup_parent",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:__elevator_change",
        "block/blk-mq-debugfs.c:queue_state_write",
        "lib/bootconfig.c:xbc_parse_key",
        "lib/bootconfig.c:__xbc_parse_keys",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234656,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585117440,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:538",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:__elevator_change",
        "block/blk-mq-debugfs.c:queue_state_write",
        "lib/bootconfig.c:xbc_parse_key",
        "lib/bootconfig.c:__xbc_parse_keys",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585117440,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585566160,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:539",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:__elevator_change",
        "block/blk-mq-debugfs.c:queue_state_write",
        "lib/bootconfig.c:xbc_parse_key",
        "lib/bootconfig.c:__xbc_parse_keys",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585566160,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586106112,
      "name": "strim",
      "external": true,
      "loc": "lib/string_helpers.c:823",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "kernel/sched/build_utility.c:sched_dynamic_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:tracing_set_trace_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:zswap_max_write",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:__elevator_change",
        "block/blk-mq-debugfs.c:queue_state_write",
        "lib/bootconfig.c:xbc_parse_key",
        "lib/bootconfig.c:__xbc_parse_keys",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106112,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587091424,
      "name": "strim",
      "external": true,
      "loc": "lib/string_helpers.c:867",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "kernel/sched/build_utility.c:sched_dynamic_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:tracing_set_trace_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/rv/rv.c:enabled_monitors_write",
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:zswap_max_write",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:__xbc_parse_keys",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587091424,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587351536,
      "name": "strim",
      "external": true,
      "loc": "lib/string_helpers.c:867",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "kernel/sched/build_utility.c:sched_dynamic_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:tracing_set_trace_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/trace_osnoise.c:osnoise_options_write",
        "kernel/trace/trace_osnoise.c:osnoise_options_write",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/rv/rv.c:enabled_monitors_write",
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:zswap_max_write",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:__xbc_parse_keys",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351536,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637760,
      "name": "strim",
      "external": true,
      "loc": "lib/string_helpers.c:884",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify",
        "kernel/sched/build_utility.c:sched_dynamic_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/misc.c:misc_cg_max_write",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:tracing_set_trace_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/trace_osnoise.c:osnoise_options_write",
        "kernel/trace/trace_osnoise.c:osnoise_options_write",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_assignment",
        "kernel/trace/rv/rv.c:enabled_monitors_write",
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:zswap_writeback_write",
        "mm/memcontrol.c:zswap_max_write",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:swap_high_write",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "fs/debugfs/file.c:debugfs_write_file_str",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/lsm.c:do_setattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:__xbc_parse_keys",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637760,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503865072,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503865072,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236493440,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/mtd/nand/raw/nand_base.c:sanitize_string",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236493440,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297725264,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/lpar.c:cmo_free_hint",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297725264,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279761580,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279761580,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589689776,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689776,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589415568,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589415568,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590133152,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590133152,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * strim(char * s)
```

```json
{
  "name": "strim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590183536,
      "name": "strim",
      "external": true,
      "loc": "lib/string.c:500",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_action_params",
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs",
        "mm/zswap.c:__zswap_param_set",
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:memory_low_write",
        "mm/memcontrol.c:memory_min_write",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_policy",
        "drivers/md/dm-init.c:str_field_delimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183536,
      "name": "strim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
