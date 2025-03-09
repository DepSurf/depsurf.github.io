# Function: <code>__task_pid_nr_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491696,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:520",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/capability.c:SyS_capget",
        "kernel/capability.c:SyS_capset",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:get_signal",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:sys_gettid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sched/core.c:schedule_tail",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/cgroup.c:pidlist_array_load",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/thread_self.c:proc_thread_self_readlink",
        "fs/proc/thread_self.c:proc_thread_self_follow_link",
        "ipc/msg.c:do_msgsnd",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_get",
        "lib/dynamic_debug.c:dynamic_emit_prefix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491696,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505616,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:520",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/capability.c:SyS_capset",
        "kernel/capability.c:SyS_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:sys_gettid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_readlink",
        "ipc/msg.c:do_msgsnd",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505616,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526288,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:520",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/capability.c:SyS_capset",
        "kernel/capability.c:SyS_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:sys_gettid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "ipc/msg.c:do_msgsnd",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526288,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513872,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:521",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/capability.c:SyS_capset",
        "kernel/capability.c:SyS_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:sys_getppid",
        "kernel/sys.c:sys_gettid",
        "kernel/sys.c:sys_getpid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513872,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540640,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:390",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/capability.c:SyS_capset",
        "kernel/capability.c:SyS_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:sys_getppid",
        "kernel/sys.c:sys_gettid",
        "kernel/sys.c:sys_getpid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540640,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568144,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:415",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_kill",
        "kernel/signal.c:__do_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__x64_sys_getppid",
        "kernel/sys.c:__x64_sys_gettid",
        "kernel/sys.c:__x64_sys_getpid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568144,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605328,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:422",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__x64_sys_getppid",
        "kernel/sys.c:__x64_sys_gettid",
        "kernel/sys.c:__x64_sys_getpid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605328,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629392,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__x64_sys_getppid",
        "kernel/sys.c:__x64_sys_gettid",
        "kernel/sys.c:__x64_sys_getpid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629392,
      "name": "__task_pid_nr_ns",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654944,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__x64_sys_getppid",
        "kernel/sys.c:__x64_sys_gettid",
        "kernel/sys.c:__x64_sys_getpid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654944,
      "name": "__task_pid_nr_ns",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685808,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:491",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getppid",
        "kernel/sys.c:__do_sys_gettid",
        "kernel/sys.c:__do_sys_getpid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:fixup_pi_state_owner",
        "kernel/futex.c:wake_futex_pi",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/exec.c:exec_binprm",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:format_corename",
        "fs/coredump.c:format_corename",
        "fs/coredump.c:format_corename",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685808,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664208,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:492",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capget",
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getppid",
        "kernel/sys.c:__do_sys_gettid",
        "kernel/sys.c:__do_sys_getpid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:wake_futex_pi",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/exec.c:exec_binprm",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:format_corename",
        "fs/coredump.c:format_corename",
        "fs/coredump.c:format_corename",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "drivers/scsi/sg.c:sg_read",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664208,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671024,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:492",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_check_attach",
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getppid",
        "kernel/sys.c:__do_sys_gettid",
        "kernel/sys.c:__do_sys_getpid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/exec.c:exec_binprm",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "lib/dynamic_debug.c:__dynamic_emit_prefix",
        "drivers/scsi/sg.c:sg_read",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671024,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748688,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:492",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_check_attach",
        "kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getppid",
        "kernel/sys.c:__do_sys_gettid",
        "kernel/sys.c:__do_sys_getpid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/exec.c:exec_binprm",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "lib/dynamic_debug.c:__dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748688,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853088,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:492",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_check_attach",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal_locked",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getppid",
        "kernel/sys.c:__do_sys_gettid",
        "kernel/sys.c:__do_sys_getpid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/futex/core.c:handle_futex_death",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:__fixup_pi_state_owner",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/audit.c:audit_log_task_info",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/exec.c:exec_binprm",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "lib/dynamic_debug.c:__dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853088,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993808,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:492",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_check_attach",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal_locked",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getppid",
        "kernel/sys.c:__do_sys_gettid",
        "kernel/sys.c:__do_sys_getpid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/futex/core.c:handle_futex_death",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:__fixup_pi_state_owner",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/audit.c:audit_log_task_info",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/exec.c:exec_binprm",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/apparmor/notify.c:build_unotif",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "lib/dynamic_debug.c:__dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993808,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047632,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:495",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_check_attach",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal_locked",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getppid",
        "kernel/sys.c:__do_sys_gettid",
        "kernel/sys.c:__do_sys_getpid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/futex/core.c:handle_futex_death",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:__fixup_pi_state_owner",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/audit.c:audit_log_task_info",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/exec.c:exec_binprm",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/apparmor/notify.c:build_v3_unotif",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "lib/dynamic_debug.c:__dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047632,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090128,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:495",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__do_sys_capset",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_check_attach",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal_locked",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getppid",
        "kernel/sys.c:__do_sys_gettid",
        "kernel/sys.c:__do_sys_getpid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/futex/core.c:handle_futex_death",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:__fixup_pi_state_owner",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/audit.c:audit_log_task_info",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_fill_link_info",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id",
        "fs/exec.c:exec_binprm",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "security/apparmor/notify.c:build_v3_unotif",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "lib/dynamic_debug.c:__dynamic_emit_prefix",
        "drivers/gpu/drm/drm_ioctl.c:drm_getclient",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090128,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490827808,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__arm64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__arm64_sys_capset",
        "kernel/capability.c:__arm64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal",
        "kernel/signal.c:__arm64_sys_kill",
        "kernel/signal.c:__arm64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__arm64_sys_setpgid",
        "kernel/sys.c:__arm64_sys_getppid",
        "kernel/sys.c:__arm64_sys_gettid",
        "kernel/sys.c:__arm64_sys_getpid",
        "kernel/sys.c:__arm64_sys_getpriority",
        "kernel/sys.c:__arm64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:handle_futex_death",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__arm64_sys_ioprio_get",
        "block/ioprio.c:__arm64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490827808,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224859504,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__se_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__se_sys_capset",
        "kernel/capability.c:__se_sys_capget",
        "kernel/signal.c:__se_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__se_sys_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:sys_getppid",
        "kernel/sys.c:sys_gettid",
        "kernel/sys.c:sys_getpid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:fixup_pi_state_owner",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/exec.c:__do_execve_file",
        "fs/userfaultfd.c:handle_userfault",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:fill_psinfo",
        "fs/binfmt_elf_fdpic.c:fill_prstatus",
        "fs/binfmt_elf_fdpic.c:fill_prstatus",
        "fs/binfmt_elf_fdpic.c:fill_prstatus",
        "fs/binfmt_elf_fdpic.c:fill_prstatus",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:format_corename",
        "fs/coredump.c:format_corename",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:do_mq_timedsend",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "drivers/scsi/sg.c:sg_check_file_access",
        "drivers/scsi/sg.c:sg_check_file_access",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_autobind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859504,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283662208,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__se_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__se_sys_capset",
        "kernel/capability.c:__se_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:sys_getppid",
        "kernel/sys.c:sys_gettid",
        "kernel/sys.c:sys_getpid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:handle_futex_death",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_autobind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283662208,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271500140,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__se_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__se_sys_capset",
        "kernel/capability.c:__se_sys_capget",
        "kernel/signal.c:__se_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__se_sys_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:sys_getppid",
        "kernel/sys.c:sys_gettid",
        "kernel/sys.c:sys_getpid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:handle_futex_death",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/exec.c:__do_execve_file",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_autobind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271500140,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631264,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__x64_sys_getppid",
        "kernel/sys.c:__x64_sys_gettid",
        "kernel/sys.c:__x64_sys_getpid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631264,
      "name": "__task_pid_nr_ns",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559600,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__x64_sys_getppid",
        "kernel/sys.c:__x64_sys_gettid",
        "kernel/sys.c:__x64_sys_getpid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559600,
      "name": "__task_pid_nr_ns",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628528,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__x64_sys_getppid",
        "kernel/sys.c:__x64_sys_gettid",
        "kernel/sys.c:__x64_sys_getpid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628528,
      "name": "__task_pid_nr_ns",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct * task, enum pid_type type, struct pid_namespace * ns)
```

```json
{
  "name": "__task_pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662416,
      "name": "__task_pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_set_tid_address",
        "kernel/fork.c:__x64_sys_set_tid_address",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget",
        "kernel/signal.c:do_rt_tgsigqueueinfo",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__send_signal",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__x64_sys_getppid",
        "kernel/sys.c:__x64_sys_gettid",
        "kernel/sys.c:__x64_sys_getpid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_procs_show",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/events/core.c:perf_event_pid_type",
        "fs/userfaultfd.c:handle_userfault",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/realpath.c:tomoyo_get_local_path",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "lib/dynamic_debug.c:dynamic_emit_prefix",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662416,
      "name": "__task_pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
