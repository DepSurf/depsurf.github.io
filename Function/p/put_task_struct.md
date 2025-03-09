# Function: <code>put_task_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579370445,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378405,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:delayed_put_task_struct",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419281,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:SyS_ptrace",
        "kernel/ptrace.c:compat_SyS_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457698,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502663,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515617,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579538882,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579588383,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_find_cpu",
        "kernel/sched/fair.c:task_numa_find_cpu",
        "kernel/sched/fair.c:task_numa_find_cpu",
        "kernel/sched/fair.c:task_numa_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634398,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579641538,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676763,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679548,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:__rwsem_do_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744211,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801694,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838250,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899529,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579988068,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:css_task_iter_next",
        "kernel/cgroup.c:css_task_iter_end",
        "kernel/cgroup.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580132702,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580150202,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580250762,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580398335,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485280,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    },
    {
      "addr": 18446744071580748503,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580817386,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/mempolicy.c:SyS_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580887921,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages",
        "mm/migrate.c:SyS_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936741,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953570,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266186,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430065,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445329,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_map_files_get_link",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:oom_adj_write",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_pid_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471902,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:seq_show",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480725,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_follow_link",
        "fs/proc/namespaces.c:proc_ns_dir_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582602290,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005295,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2028",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485280,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378178,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393114,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432651,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579470914,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516727,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529729,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579568197,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_q"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579600806,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579649390,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579656762,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579695989,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767008,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801023,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829697,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579867182,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579929643,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580028037,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:css_task_iter_end",
        "kernel/cgroup.c:css_task_iter_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580166791,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580184554,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293898,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580509881,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580569864,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580867672,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580942794,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/mempolicy.c:SyS_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018109,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages",
        "mm/migrate.c:SyS_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581083713,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102649,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431946,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611688,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632674,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656816,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665595,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846577,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587883350,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2167",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567584,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579124133,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397218,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413450,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453003,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491314,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538821,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553046,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579593169,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_q"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579628416,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674058,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579681279,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579723095,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794010,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829382,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858721,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579922878,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579960347,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580062128,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:css_task_iter_end",
        "kernel/cgroup.c:css_task_iter_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580207208,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580225169,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580337770,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580574792,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580636928,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    },
    {
      "addr": 18446744071580935526,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581015607,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092338,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581177862,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513066,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581700231,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720962,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745360,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581754155,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582942577,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588100089,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched.h:2254",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634480,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579119765,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384250,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400806,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579440919,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479441,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579525744,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539713,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579577377,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_q"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605841,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648211,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579658594,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719327,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579790988,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829339,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579866397,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579932037,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961835,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580057774,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065523,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215278,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580235280,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580350986,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580605301,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580668953,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    },
    {
      "addr": 18446744071580979542,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580987584,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056584,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139158,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224166,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581565805,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758467,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776214,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799643,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808288,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582993566,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": [
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ]
    },
    {
      "addr": 18446744071588325724,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580663904,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582991488,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579133561,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411104,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579428854,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469223,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507313,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551744,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579566485,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579607073,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_q"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638817,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679448,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579689386,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579751818,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824546,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869471,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910045,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579977557,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010555,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580108265,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580118370,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580266622,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580286480,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580404478,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580686053,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753982,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581082246,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581091312,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581167889,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581261158,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354966,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581709933,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905445,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925686,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949140,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581957840,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583157086,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588891845,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748944,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579143205,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425467,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444112,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479354,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579531746,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579580416,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579594661,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579637189,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_q"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579667830,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714135,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729942,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786318,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579857721,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579903866,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954152,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580028667,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580061215,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580167433,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580177757,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580327084,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580347805,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580466026,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580629171,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580818015,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071580888244,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581221220,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581231862,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311036,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407338,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581500146,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876753,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582086083,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582109926,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135639,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142189,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583362523,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589270137,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589121092,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:93",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757568,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580884784,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579208641,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458891,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477655,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579512938,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579567858,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579618048,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579632437,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579674869,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_q"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724762,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752295,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760566,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832808,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579835405,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:__rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905280,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579951490,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000691,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580075547,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580105227,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215353,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580225748,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580380021,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580403869,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580521866,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580697918,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884687,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580961993,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581304932,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581314852,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392588,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581490826,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585986,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961873,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582181432,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582204870,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229623,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582236813,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481259,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589512705,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354738,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:95",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958096,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579222379,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475947,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496940,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532350,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590959,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642619,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657282,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579706800,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579737529,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579780933,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788192,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579867725,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579941364,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990044,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580043976,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580119007,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580151851,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580263319,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580274422,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580432768,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456772,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580578218,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580770426,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580981962,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057917,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581384534,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581425454,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504725,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600508,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696848,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582094516,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582347926,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369909,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582393879,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401239,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583665577,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589971824,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:112",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053392,
      "name": "put_task_struct",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224699,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502027,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522940,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579558494,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617039,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668075,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579694370,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579748896,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579780409,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826437,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579834912,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579916349,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991540,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580040176,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093064,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168370,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200644,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311623,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322538,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580481520,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580505732,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580625306,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580819489,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581036090,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113677,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581445478,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581489662,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569125,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671180,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770288,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582171876,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582445001,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582469653,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492791,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582500199,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771705,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590199232,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587053181,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109392,
      "name": "put_task_struct",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579245528,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579521551,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:wait_for_vfork_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579550896,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590606,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648106,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687207,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579699865,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734394,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_destroy_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784632,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579810257,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865895,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873325,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579956542,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579960494,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047012,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580094853,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155604,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580273858,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381623,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580395596,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580566311,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580591583,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724858,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580927771,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034305,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215334,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071581297616,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581650870,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581695399,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782476,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889556,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581991463,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582408830,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518020,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_req_aux_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740713,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582763530,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582791747,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582802439,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161860,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591215134,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587884381,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:123",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145536,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581292096,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579238383,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579502895,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:wait_for_vfork_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532137,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579570622,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579628610,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665480,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677465,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714330,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_destroy_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764912,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801588,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858201,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579867000,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944702,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948638,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030212,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580075507,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:trc_del_holdout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140062,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257456,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368535,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580382790,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554364,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580751,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714330,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580923658,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042302,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258167,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071581341664,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581699021,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581735392,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581742167,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834417,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913433,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041303,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461808,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582579283,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:__io_free_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582812792,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835898,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865898,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876071,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584280041,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591710270,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587946028,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185584,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581336320,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579242865,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516172,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539882,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575540,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635223,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579672308,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579684165,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579721562,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_destroy_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579772624,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803845,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579867689,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579875535,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952426,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591650371,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030948,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580077575,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580144583,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580262416,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580371559,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580385731,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580557524,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583987,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:cmd_attr_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719098,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580927018,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056218,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_vma_seq_stop",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276791,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071581360125,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581720729,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581763806,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770395,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581865257,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581938933,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992388,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067767,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582488825,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655974,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_exit_workers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582841527,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582863681,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582893991,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582904407,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584306565,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591657635,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587827232,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:110",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203808,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581355584,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282993,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587881,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579612342,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579649988,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x64_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711751,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749604,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579762309,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799918,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_destroy_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864289,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899980,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579969852,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579993912,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    },
    {
      "addr": 18446744071580075275,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/sched/core_sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core_sched.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081290,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592824684,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580163460,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580211919,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580288327,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580414565,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:futex_lock_pi_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580531511,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580547882,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580727433,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754835,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:cmd_attr_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897927,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581130074,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281239,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_vma_seq_stop",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520537,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071581610590,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581993020,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582046527,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582053051,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582156793,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243173,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294628,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582377665,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582803033,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986461,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_put_and_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174295,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583197825,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583227287,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_fdinfo_open",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238663,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584693077,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592831333,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588432162,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:111",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980960,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581443584,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581603424,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336992,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678877,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704971,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744617,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579802247,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854172,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871613,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909872,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_destroy_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579979957,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580007788,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580109325,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_dl_overflow"
      ]
    },
    {
      "addr": 18446744071580202862,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215902,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594732301,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580309656,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580371022,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593915742,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_print_task_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580496552,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580627396,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:wait_for_owner_exiting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634944,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex/pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/pi.c:futex_lock_pi_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580728702,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746040,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939856,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969560,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:cmd_attr_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133479,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581402983,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577512,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867937,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071581970774,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:wake_oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_evaluate_task",
        "mm/oom_kill.c:oom_evaluate_task"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071582415908,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582486042,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582487765,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612041,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714912,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780940,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879393,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583354077,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583665428,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583695889,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583724952,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583737655,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585355249,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586036805,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594740477,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589831314,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085344,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071581785232,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071581963648,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579405616,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799220,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579830507,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579875897,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940647,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995116,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014546,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580063323,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_destroy_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140629,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580177022,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282669,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_dl_overflow"
      ]
    },
    {
      "addr": 18446744071580393982,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408830,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596484060,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580522472,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580595361,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580619896,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_print_task_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580748520,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580893396,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:wait_for_owner_exiting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901424,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex/pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/pi.c:futex_lock_pi_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004366,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023134,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233253,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265288,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:cmd_attr_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444775,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581625200,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:do_bpf_send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753969,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942346,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_task_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581955159,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582295249,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071582401651,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:wake_oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_evaluate_task",
        "mm/oom_kill.c:oom_evaluate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923764,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583000268,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583002357,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135273,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242096,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313116,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583426997,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583937101,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584272414,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305969,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584337016,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_count",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584351111,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586036894,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586104017,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586757153,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586872649,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596492637,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256800,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071582218592,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417648,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579847375,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579879592,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579925209,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990711,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580049580,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068290,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580117755,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_destroy_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221591,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243854,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580349981,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_dl_overflow"
      ]
    },
    {
      "addr": 18446744071580462672,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580477598,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597025702,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580595402,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580668865,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692798,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_print_task_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831070,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930911,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977252,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:wait_for_owner_exiting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985392,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/futex/pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/pi.c:futex_lock_pi_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092958,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581111514,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327605,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360440,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:cmd_attr_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541895,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581560481,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:timerlat_fd_release",
        "kernel/trace/trace_osnoise.c:stop_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764656,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:do_bpf_send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913905,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143272,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582496017,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071582607684,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:wake_oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_evaluate_task",
        "mm/oom_kill.c:oom_evaluate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140164,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583209136,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583212231,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage_bdev_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583345593,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583461808,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583532444,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583647749,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584151338,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584501033,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584535809,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584567096,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_count",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584580391,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586271972,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586342657,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587023723,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_put_task_remote"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587138502,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587257061,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "rust/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "rust/helpers.c:rust_helper_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597033837,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:122",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322800,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071582418896,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579449624,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885167,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579918248,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579964537,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030119,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092076,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580111260,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop_put",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270439,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580300254,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402689,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:task_contending",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_dl_overflow"
      ]
    },
    {
      "addr": 18446744071580522375,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537422,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597955046,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580736006,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_holdout_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580758910,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_print_task_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920494,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581021535,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071092,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:wait_for_owner_exiting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080976,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/futex/pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/pi.c:futex_lock_pi_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087969,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_wake_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190484,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209386,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433909,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581466664,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:cmd_attr_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654087,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581672689,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:timerlat_fd_release",
        "kernel/trace/trace_osnoise.c:stop_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902338,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach",
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_dealloc",
        "kernel/trace/bpf_trace.c:do_bpf_send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582039585,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582292499,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:bpf_iter_task_vma_destroy",
        "kernel/bpf/task_iter.c:bpf_iter_task_vma_new",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582664465,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446744071582777940,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:wake_oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_evaluate_task",
        "mm/oom_kill.c:oom_evaluate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323286,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583444704,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_process_madvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446669,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_read_folio_bdev_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583581688,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583654896,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726796,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583842581,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584365610,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584724968,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584767609,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:lstats_write",
        "fs/proc/base.c:lstats_show_proc",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584798984,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/fd.c:proc_readfd_count",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584811607,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586529281,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586609441,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587304149,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_put_task_remote"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424630,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587506261,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "rust/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "rust/helpers.c:rust_helper_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597965805,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:125",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:__ldsem_wake_readers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376736,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071582578352,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490376996,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_vcpu_yield_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490634904,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490661564,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490714128,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__arm64_compat_sys_ptrace",
        "kernel/ptrace.c:__arm64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490784136,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490845584,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490873720,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490927744,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__arm64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490960044,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491010988,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491022144,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491119804,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491181336,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491241160,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491302268,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/kcmp.c:__arm64_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491391672,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491441652,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491564128,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491580064,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491757232,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491784352,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491926988,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492144480,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492388448,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    },
    {
      "addr": 18446603336492481580,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492851992,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492908792,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493006040,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493114960,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493231232,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493726336,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494060056,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494081608,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494115688,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494124464,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495574064,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503946368,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492322416,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224712712,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 3224737272,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 3224773832,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 3224820752,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 3224873664,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3224891624,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_destroy_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 3224947272,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 3225010048,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3225032844,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 3225121008,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 3225204808,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3225253688,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 3225300132,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 3225387172,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3225425276,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 3225528616,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 3225542152,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225705608,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 3225731912,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3225864156,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:wakeup_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3226024296,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 3226276296,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3226355788,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 3226653104,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226700120,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227252200,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3227517372,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3227538164,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3227565388,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3227574024,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3228935232,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 3236555400,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283453836,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283485908,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283538272,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_compat_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283609240,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283683844,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283705868,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283780880,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283820432,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283876996,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283899108,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284010836,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284082852,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284142456,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284226516,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284331268,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284382736,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284542080,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284560052,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284798508,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284832544,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285025640,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285351044,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285649940,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285766744,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 13835058055286239776,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286312864,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286434540,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286591448,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286743060,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287333476,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287717936,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287751080,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287786544,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287797272,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289668056,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297799524,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285760112,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271390004,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271405856,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271434528,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271467774,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271512494,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271527984,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271564428,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271618680,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271627438,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271694480,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271728272,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271769976,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271813322,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271872488,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271901828,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271977742,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271989798,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272078556,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272099504,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272205744,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272306234,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272499660,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272547482,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272800268,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272832498,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273336572,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273559488,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273567382,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273599144,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273607582,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274740902,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279809790,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223547,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475691,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496604,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579534798,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593343,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579644395,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579670690,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579724848,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579756265,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800053,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807264,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888461,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579960276,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580008912,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580062264,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137570,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580169444,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280423,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291338,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450320,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474532,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580594106,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580788289,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004938,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082525,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581414326,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581458510,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537861,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639916,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739024,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582140612,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413737,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438389,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461527,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468935,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583740441,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589801520,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078240,
      "name": "put_task_struct",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579158475,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404587,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425488,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463582,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579521983,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572779,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599042,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579653408,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686649,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579733184,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579741760,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823413,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898116,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947692,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580007112,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580082722,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580117048,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580227857,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580238708,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397392,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580421573,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580540634,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580734465,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951082,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029709,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581356838,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581400702,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479621,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580876,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677664,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582078052,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582351433,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582375557,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582398759,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406167,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677497,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589523950,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586701101,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025424,
      "name": "put_task_struct",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224619,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475611,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496524,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532078,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590623,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641659,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579667922,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579711600,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579740777,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786805,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795280,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876621,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579951812,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000448,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580053336,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580128642,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580160916,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271671,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282586,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580441568,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580465780,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580585354,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580779537,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996138,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581073725,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581405526,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581449710,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529173,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631228,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730336,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582131092,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404217,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428869,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452007,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582459415,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583724217,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590244928,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587007741,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069440,
      "name": "put_task_struct",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_task_struct(struct task_struct * t)
```

```json
{
  "name": "put_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579230021,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507459,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529109,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579565150,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579624237,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675899,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579702082,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579756542,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_up_q",
        "kernel/sched/core.c:wake_q_add_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788471,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829925,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579840956,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579922095,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579998196,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047393,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580104094,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180514,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580220478,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325198,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580336465,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580497190,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580521454,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580642250,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580837822,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057245,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135433,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581469638,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581514190,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:end_swap_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596444,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697553,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581798592,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582204135,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582482108,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509269,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_stop",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:lstats_write",
        "fs/proc/base.c:lstats_show_proc",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582532368,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539767,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583825036,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:__report_access",
        "security/yama/yama_lsm.c:__report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590295982,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587114909,
      "name": "put_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130960,
      "name": "put_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void put_task_struct(struct task_struct * t)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void put_task_struct(struct task_struct * t)
```
</details>
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
