# Function: <code>get_task_struct</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct task_struct * get_task_struct(struct task_struct * t)
```

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224606,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501913,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522887,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579616929,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654604,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668006,
      "name": "get_task_struct",
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
      "addr": 18446744071579694157,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579748864,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579778070,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826268,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833048,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908786,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917975,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579988542,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039853,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092706,
      "name": "get_task_struct",
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
      "addr": 18446744071580168578,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197323,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311360,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322491,
      "name": "get_task_struct",
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
      "addr": 18446744071580481439,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580625701,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581021974,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581106128,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581492394,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569087,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671143,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772662,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582477113,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771593,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590198943,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587059290,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106128,
      "name": "get_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579245414,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579530280,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579550827,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647975,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687131,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579699768,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734721,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579784577,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579810293,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865816,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871045,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952654,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579956459,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962855,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580036702,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093074,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155187,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580265915,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381306,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580395517,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580566192,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580725282,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202137,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296741,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697911,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782415,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889495,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581993417,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505853,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_poll_add_prep",
        "fs/io_uring.c:io_arm_poll_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582775293,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583597011,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:expunge_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609536,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645991,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161710,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591214724,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587890727,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:115",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579238262,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579513093,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532068,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579628474,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665403,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677368,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714668,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579748397,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801624,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579859303,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579875545,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579941007,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944619,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950999,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580019919,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580075938,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139635,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249787,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368218,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580382704,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554240,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714754,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243924,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340618,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744757,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833759,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913176,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042985,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607669,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582848637,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583717363,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:expunge_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583729888,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583767175,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584279886,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591709860,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587952071,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:100",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579242746,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516035,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539816,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635093,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579672235,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579684072,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579721900,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579755540,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803881,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579866919,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579884553,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948719,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952347,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591654175,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580020559,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580077314,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580144162,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254923,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580371242,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580385652,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580557408,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719543,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260771,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359114,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772917,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581864607,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581938680,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992334,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582069446,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660891,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582877047,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583741867,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:expunge_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583754267,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583791367,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584306414,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591657241,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587839381,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:102",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579282874,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587744,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579612276,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711621,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749531,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579762216,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800316,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579838483,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900016,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579971351,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579984158,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580075077,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/sched/core_sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core_sched.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580077826,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081211,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592828911,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580152335,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580211714,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580287906,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406235,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580531194,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580547812,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580727317,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898453,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501746,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611900,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055546,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582156143,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242920,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294574,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582383494,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985853,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583210663,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103531,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:expunge_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584115883,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584154127,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584692926,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592830963,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588444517,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:103",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579336871,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678741,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704899,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579802120,
      "name": "get_task_struct",
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
      "addr": 18446744071579854099,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871526,
      "name": "get_task_struct",
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
      "addr": 18446744071579910340,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:__smpboot_create_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952960,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580007824,
      "name": "get_task_struct",
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
      "addr": 18446744071580089715,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:start_dl_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580202638,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580213715,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215823,
      "name": "get_task_struct",
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
      "addr": 18446744071594737547,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298407,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370821,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593915552,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_print_task_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580496124,
      "name": "get_task_struct",
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
      "addr": 18446744071580642391,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_wake_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580728394,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745975,
      "name": "get_task_struct",
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
      "addr": 18446744071580939734,
      "name": "get_task_struct",
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
      "addr": 18446744071581134066,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850687,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972165,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_evaluate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492355,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582611415,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714659,
      "name": "get_task_struct",
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
      "addr": 18446744071582780886,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582886376,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707427,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584699938,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:expunge_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584714662,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584752622,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585355150,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586036189,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594740125,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589842090,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579405495,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799005,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579830435,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940520,
      "name": "get_task_struct",
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
      "addr": 18446744071579995043,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014454,
      "name": "get_task_struct",
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
      "addr": 18446744071580063860,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:__smpboot_create_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580112096,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580177058,
      "name": "get_task_struct",
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
      "addr": 18446744071580261943,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:start_dl_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580393758,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406099,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408751,
      "name": "get_task_struct",
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
      "addr": 18446744071596489531,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580510327,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580596793,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580619672,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_print_task_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580748092,
      "name": "get_task_struct",
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
      "addr": 18446744071580908999,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_wake_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004026,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023063,
      "name": "get_task_struct",
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
      "addr": 18446744071581233131,
      "name": "get_task_struct",
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
      "addr": 18446744071581445396,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625445,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943095,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_task_from_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954048,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_group_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582277724,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406582,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_evaluate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007153,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134647,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241843,
      "name": "get_task_struct",
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
      "addr": 18446744071583313062,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435749,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584318371,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585392034,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:expunge_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585407494,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585447614,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586036788,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586103918,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586760348,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586871994,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596492285,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed"
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
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579417527,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579847142,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579879520,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990584,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580049507,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068198,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580118292,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:__smpboot_create_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580173920,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__do_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243890,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_assign"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328007,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:start_dl_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580462206,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474883,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580477519,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597030843,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582455,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580670297,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692599,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_print_task_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830652,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930858,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992871,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581092618,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581111443,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327483,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542452,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558751,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:timerlat_fd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764901,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142144,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_group_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478634,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612569,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_evaluate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583212169,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage_bdev_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583344967,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583461555,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:find_mm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583532390,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583653856,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:__add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584548326,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585622674,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:expunge_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585638274,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585678840,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586271880,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586342558,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027135,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587137912,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587257461,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "rust/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "rust/helpers.c:rust_helper_get_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597033485,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:114",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed"
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
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579449510,
      "name": "get_task_struct",
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
      "addr": 18446744071579884934,
      "name": "get_task_struct",
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
      "addr": 18446744071579918176,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580029992,
      "name": "get_task_struct",
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
      "addr": 18446744071580092003,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580110838,
      "name": "get_task_struct",
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
      "addr": 18446744071580163509,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:__smpboot_create_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580220292,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580300290,
      "name": "get_task_struct",
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
      "addr": 18446744071580382975,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:start_dl_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580521870,
      "name": "get_task_struct",
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
      "addr": 18446744071580534707,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537343,
      "name": "get_task_struct",
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
      "addr": 18446744071597960235,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646583,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580737145,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580758711,
      "name": "get_task_struct",
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
      "addr": 18446744071580920076,
      "name": "get_task_struct",
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
      "addr": 18446744071581021482,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087919,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_wake_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190143,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209315,
      "name": "get_task_struct",
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
      "addr": 18446744071581433787,
      "name": "get_task_struct",
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
      "addr": 18446744071581654810,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670879,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:timerlat_fd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883637,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_send_signal_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291834,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:bpf_iter_task_vma_new",
        "kernel/bpf/task_iter.c:task_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582647201,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_remove_from_owner",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784133,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_evaluate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446607,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_read_folio_bdev_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583581062,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583654643,
      "name": "get_task_struct",
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
      "addr": 18446744071583726742,
      "name": "get_task_struct",
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
      "addr": 18446744071583848076,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:__add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584780456,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585869394,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:expunge_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585884962,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585925678,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586529194,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586609342,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326985,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587413472,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "io_uring/register.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/register.c:__io_uring_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424090,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587506661,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "rust/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "rust/helpers.c:rust_helper_get_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597965453,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:116",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:down_read_failed"
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
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490634808,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490661504,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490784020,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490828072,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490845512,
      "name": "get_task_struct",
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
      "addr": 18446603336490873464,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490927528,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__arm64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490958088,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491010804,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491024092,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491111348,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491122712,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491185464,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491240792,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491302000,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/kcmp.c:__arm64_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491389588,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491428844,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491563776,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491580016,
      "name": "get_task_struct",
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
      "addr": 18446603336491757180,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491927436,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492374012,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492480452,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492911400,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493006004,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493114920,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493226856,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494097128,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495573944,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503945960,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224712568,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 3224737164,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 3224820608,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 3224859732,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 3224873592,
      "name": "get_task_struct",
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
      "addr": 3224891876,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224947024,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3225009868,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3225029268,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 3225113804,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 3225123200,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 3225209104,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3225253316,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 3225299904,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 3225387572,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225420792,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 3225528308,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3225542092,
      "name": "get_task_struct",
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
      "addr": 3225705556,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 3225864216,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 3226259356,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3226354684,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3226703132,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 3227548108,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3228935168,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 3236554984,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283453696,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283485796,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283609128,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283661716,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283683748,
      "name": "get_task_struct",
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
      "addr": 13835058055283706408,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283780588,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283815368,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283876772,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283897712,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284002164,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284013964,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284088776,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284142064,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284226220,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284331676,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284375332,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284541636,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284559984,
      "name": "get_task_struct",
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
      "addr": 13835058055284798436,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285026444,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285629972,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285765560,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286316684,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286434492,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286591396,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286745324,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287765212,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289667884,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297799008,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271389892,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271405810,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271467688,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271499742,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271512432,
      "name": "get_task_struct",
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
      "addr": 18446743936271527808,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271564236,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271618498,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271628098,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271690176,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271696502,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271733194,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271769606,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271813146,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271872690,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271893580,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271977378,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271989772,
      "name": "get_task_struct",
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
      "addr": 18446743936272078506,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272208144,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272480302,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272546488,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272834812,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273583966,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274740804,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279809458,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
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
struct task_struct * get_task_struct(struct task_struct * t)
```

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223454,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475577,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496551,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593233,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579630925,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579644326,
      "name": "get_task_struct",
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
      "addr": 18446744071579670477,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579724816,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753926,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799884,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805400,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880898,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890087,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579957278,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580008589,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580061906,
      "name": "get_task_struct",
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
      "addr": 18446744071580137778,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580166123,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280160,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291291,
      "name": "get_task_struct",
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
      "addr": 18446744071580450239,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580594501,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580990822,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074976,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581461242,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537823,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639879,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741398,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582445849,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583740329,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589801231,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
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
      "addr": 18446744071581074976,
      "name": "get_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
struct task_struct * get_task_struct(struct task_struct * t)
```

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579158382,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404473,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425435,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579521873,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579559260,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572710,
      "name": "get_task_struct",
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
      "addr": 18446744071579598829,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579653376,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579684298,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579733020,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739912,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579815890,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825047,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579895134,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947261,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006754,
      "name": "get_task_struct",
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
      "addr": 18446744071580082930,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580113739,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580227616,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580238661,
      "name": "get_task_struct",
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
      "addr": 18446744071580397311,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542037,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937014,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022160,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581403434,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479583,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580839,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679446,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582383017,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677385,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589523679,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586707210,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022160,
      "name": "get_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
struct task_struct * get_task_struct(struct task_struct * t)
```

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224526,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475497,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496471,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590513,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579628188,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641590,
      "name": "get_task_struct",
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
      "addr": 18446744071579667709,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579711568,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738438,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786636,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793416,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869058,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579878247,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948814,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000125,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052978,
      "name": "get_task_struct",
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
      "addr": 18446744071580128850,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157595,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271408,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282539,
      "name": "get_task_struct",
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
      "addr": 18446744071580441487,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580585749,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580982022,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066176,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581452442,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529135,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631191,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732710,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582436329,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583724105,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590244639,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587013850,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066176,
      "name": "get_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
struct task_struct * get_task_struct(struct task_struct * t)
```

```json
{
  "name": "get_task_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579229923,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507346,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529057,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579624123,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662269,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675830,
      "name": "get_task_struct",
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
      "addr": 18446744071579701869,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579756505,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr",
        "kernel/sched/core.c:do_sched_setscheduler",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786098,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_find_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829664,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579840008,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914482,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579923847,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995246,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047065,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580103757,
      "name": "get_task_struct",
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
      "addr": 18446744071580180723,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:__get_task_for_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580209963,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:mark_wake_futex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580324960,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580336418,
      "name": "get_task_struct",
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
      "addr": 18446744071580497112,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642645,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042877,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:alloc_perf_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127696,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process"
      ]
    },
    {
      "addr": 18446744071581516906,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595828,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697500,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800998,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582516447,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583824963,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_task_prctl",
        "security/yama/yama_lsm.c:report_access",
        "security/yama/yama_lsm.c:report_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590295720,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587121018,
      "name": "get_task_struct",
      "external": false,
      "loc": "include/linux/sched/task.h:108",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127696,
      "name": "get_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct task_struct * get_task_struct(struct task_struct * t)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct task_struct * get_task_struct(struct task_struct * t)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct task_struct * get_task_struct(struct task_struct * t)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct task_struct * get_task_struct(struct task_struct * t)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct task_struct * get_task_struct(struct task_struct * t)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct task_struct * get_task_struct(struct task_struct * t)
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
