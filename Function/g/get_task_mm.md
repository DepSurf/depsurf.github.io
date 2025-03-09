# Function: <code>get_task_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579358704,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:780",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/sys.c:k_getrusage",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/migrate.c:SyS_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_get_link",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_statm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358704,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579365600,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:838",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/sys.c:k_getrusage",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/migrate.c:SyS_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365600,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383696,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:992",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:k_getrusage",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383696,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371104,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1039",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371104,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397888,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1051",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397888,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414672,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1120",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414672,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446960,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1176",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446960,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579463664,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1193",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463664,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490032,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490032,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519152,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1222",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519152,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499728,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1219",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499728,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504000,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1225",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504000,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574672,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1304",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574672,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671956,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1376",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_access"
      ],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_pid_ksm_merging_pages",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660256,
      "name": "get_task_mm",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579792312,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1400",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_access"
      ],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_pid_ksm_stat",
        "fs/proc/base.c:proc_pid_ksm_merging_pages",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779168,
      "name": "get_task_mm",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579840200,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1541",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_access"
      ],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_pid_ksm_stat",
        "fs/proc/base.c:proc_pid_ksm_merging_pages",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825904,
      "name": "get_task_mm",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878008,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1537",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_access"
      ],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_pid_ksm_stat",
        "fs/proc/base.c:proc_pid_ksm_merging_pages",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863808,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490621624,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490621624,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224697976,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224697976,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283440576,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283440576,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271380014,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271380014,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579463696,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463696,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579392656,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579392656,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579463616,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463616,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct mm_struct * get_task_mm(struct task_struct * task)
```

```json
{
  "name": "get_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491408,
      "name": "get_task_mm",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491408,
      "name": "get_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
