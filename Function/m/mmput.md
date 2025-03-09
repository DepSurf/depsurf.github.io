# Function: <code>mmput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360688,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:700",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/sys.c:k_getrusage",
        "kernel/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/cpuset.c:cpuset_migrate_mm",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/migrate.c:SyS_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_pid_auxv",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_statm",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360688,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579367840,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:733",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/sys.c:k_getrusage",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:cpuset_migrate_mm",
        "kernel/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/migrate.c:SyS_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_auxv",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367840,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386048,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:887",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:k_getrusage",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:cpuset_migrate_mm",
        "kernel/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386048,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373584,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:934",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373584,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400448,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:944",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400448,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415184,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1013",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415184,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447696,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1068",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447696,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464336,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1085",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464336,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490608,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490608,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520544,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1114",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:build_map_info",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_cancel_attach",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:userfaultfd_zeropage",
        "fs/userfaultfd.c:userfaultfd_copy",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io-wq.c:io_worker_handle_work",
        "fs/io-wq.c:__io_worker_unuse",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520544,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501872,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1111",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:build_map_info",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_cancel_attach",
        "fs/exec.c:free_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:userfaultfd_zeropage",
        "fs/userfaultfd.c:userfaultfd_copy",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread_drop_mm_files",
        "fs/io-wq.c:io_impersonate_work",
        "fs/io-wq.c:__io_worker_unuse",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501872,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505392,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1117",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:build_map_info",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_cancel_attach",
        "fs/exec.c:free_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:userfaultfd_continue",
        "fs/userfaultfd.c:userfaultfd_zeropage",
        "fs/userfaultfd.c:userfaultfd_copy",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505392,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576080,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1136",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:build_map_info",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_cancel_attach",
        "fs/exec.c:free_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:userfaultfd_continue",
        "fs/userfaultfd.c:userfaultfd_writeprotect",
        "fs/userfaultfd.c:userfaultfd_zeropage",
        "fs/userfaultfd.c:userfaultfd_copy",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/iommu/io-pgfault.c:iopf_handle_single",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576080,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665824,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1208",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:build_map_info",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_cancel_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/exec.c:free_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:userfaultfd_continue",
        "fs/userfaultfd.c:userfaultfd_writeprotect",
        "fs/userfaultfd.c:userfaultfd_zeropage",
        "fs/userfaultfd.c:userfaultfd_copy",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_pid_ksm_merging_pages",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/io-pgfault.c:iopf_handle_single",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665824,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579792398,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1229",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_access"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:build_map_info",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_cancel_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/exec.c:free_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:userfaultfd_continue",
        "fs/userfaultfd.c:userfaultfd_writeprotect",
        "fs/userfaultfd.c:userfaultfd_zeropage",
        "fs/userfaultfd.c:userfaultfd_copy",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_pid_ksm_stat",
        "fs/proc/base.c:proc_pid_ksm_merging_pages",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785744,
      "name": "mmput",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579840292,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_access"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:build_map_info",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_cancel_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/exec.c:free_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:userfaultfd_continue",
        "fs/userfaultfd.c:userfaultfd_writeprotect",
        "fs/userfaultfd.c:userfaultfd_zeropage",
        "fs/userfaultfd.c:userfaultfd_copy",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_pid_ksm_stat",
        "fs/proc/base.c:proc_pid_ksm_merging_pages",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832448,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878100,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1365",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_access"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:build_map_info",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/madvise.c:__do_sys_process_madvise",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/memcontrol.c:mem_cgroup_cancel_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/exec.c:free_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:userfaultfd_move",
        "fs/userfaultfd.c:userfaultfd_poison",
        "fs/userfaultfd.c:userfaultfd_continue",
        "fs/userfaultfd.c:userfaultfd_writeprotect",
        "fs/userfaultfd.c:userfaultfd_zeropage",
        "fs/userfaultfd.c:userfaultfd_copy",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_pid_ksm_stat",
        "fs/proc/base.c:proc_pid_ksm_merging_pages",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870288,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490623520,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490623520,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224699960,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/exec.c:__do_execve_file",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_next",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:mem_rw",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224699960,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283439856,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:mem_rw",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283439856,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271387462,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access"
      ],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/exec.c:__do_execve_file",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_next",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:mem_rw",
        "fs/proc/base.c:mem_rw",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271380840,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464272,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464272,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393232,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393232,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464192,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464192,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void mmput(struct mm_struct * mm)
```

```json
{
  "name": "mmput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493232,
      "name": "mmput",
      "external": true,
      "loc": "kernel/fork.c:1100",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/ptrace.c:ptrace_access_vm",
        "kernel/sys.c:getrusage",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm",
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/util.c:get_cmdline",
        "mm/memory.c:access_process_vm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/hmm.c:hmm_range_unregister",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493232,
      "name": "mmput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
