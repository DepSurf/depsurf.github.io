# Function: <code>find_task_by_vpid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494240,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:459",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capget",
        "kernel/ptrace.c:ptrace_get_task_struct",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/time/posix-timers.c:SyS_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:check_clock",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/migrate.c:SyS_move_pages",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_get",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494240,
      "name": "find_task_by_vpid",
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508224,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:459",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capget",
        "kernel/ptrace.c:ptrace_get_task_struct",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/time/posix-timers.c:SyS_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:check_clock",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/migrate.c:SyS_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508224,
      "name": "find_task_by_vpid",
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528896,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:459",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:SyS_capget",
        "kernel/ptrace.c:ptrace_get_task_struct",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/time/posix-timers.c:SyS_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:check_clock",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528896,
      "name": "find_task_by_vpid",
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516416,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:460",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:SyS_capget",
        "kernel/ptrace.c:ptrace_get_task_struct",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:check_clock",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516416,
      "name": "find_task_by_vpid",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542528,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:SyS_capget",
        "kernel/ptrace.c:ptrace_get_task_struct",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "kernel/sched/core.c:SyS_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:check_clock",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542528,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570192,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:341",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:check_clock",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/futex_compat.c:__x32_compat_sys_get_robust_list",
        "kernel/futex_compat.c:__ia32_compat_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570192,
      "name": "find_task_by_vpid",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607376,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:350",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:check_clock",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607376,
      "name": "find_task_by_vpid",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631712,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:check_clock",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631712,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657264,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657264,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579689824,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689728,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579667995,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:420",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667904,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579674811,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:420",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674720,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579752459,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:420",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core_sched.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x64_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752368,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579857265,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:420",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex/syscalls.c:__ia32_sys_get_robust_list",
        "kernel/futex/syscalls.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857152,
      "name": "find_task_by_vpid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579998433,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:420",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex/syscalls.c:__ia32_sys_get_robust_list",
        "kernel/futex/syscalls.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998304,
      "name": "find_task_by_vpid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580052929,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:423",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex/syscalls.c:__ia32_sys_get_robust_list",
        "kernel/futex/syscalls.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052800,
      "name": "find_task_by_vpid",
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580095393,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:423",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex/syscalls.c:__ia32_sys_get_robust_list",
        "kernel/futex/syscalls.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/huge_memory.c:split_huge_pages_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095264,
      "name": "find_task_by_vpid",
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490830984,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__arm64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__arm64_sys_prlimit64",
        "kernel/sys.c:__arm64_sys_getsid",
        "kernel/sys.c:__arm64_sys_getpgid",
        "kernel/sys.c:__arm64_sys_setpgid",
        "kernel/sys.c:__arm64_sys_getpriority",
        "kernel/sys.c:__arm64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__arm64_sys_sched_getattr",
        "kernel/sched/core.c:__arm64_sys_sched_getparam",
        "kernel/sched/core.c:__arm64_sys_sched_getscheduler",
        "kernel/sched/core.c:__arm64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__arm64_compat_sys_get_robust_list",
        "kernel/futex.c:__arm64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__arm64_sys_ioprio_get",
        "block/ioprio.c:__arm64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490830984,
      "name": "find_task_by_vpid",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224861728,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_getattr",
        "kernel/sched/core.c:__se_sys_sched_getparam",
        "kernel/sched/core.c:__se_sys_sched_getscheduler",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__se_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224861728,
      "name": "find_task_by_vpid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283665520,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_sys_getsid",
        "kernel/sys.c:__se_sys_getpgid",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_getattr",
        "kernel/sched/core.c:__se_sys_sched_getparam",
        "kernel/sched/core.c:__se_sys_sched_getscheduler",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__se_compat_sys_get_robust_list",
        "kernel/futex.c:__se_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283665520,
      "name": "find_task_by_vpid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271502362,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_sys_getsid",
        "kernel/sys.c:__se_sys_getpgid",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_getattr",
        "kernel/sched/core.c:__se_sys_sched_getparam",
        "kernel/sched/core.c:__se_sys_sched_getscheduler",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__se_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271502362,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633584,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633584,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561904,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561904,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630848,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630848,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct task_struct * find_task_by_vpid(pid_t vnr)
```

```json
{
  "name": "find_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664656,
      "name": "find_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:353",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_send_specific",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/net_namespace.c:get_net_ns_by_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664656,
      "name": "find_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
