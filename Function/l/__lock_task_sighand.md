# Function: <code>__lock_task_sighand</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431328,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1209",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:do_send_sig_info",
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:send_sigqueue",
        "kernel/sys.c:k_getrusage",
        "kernel/sched/auto_group.c:autogroup_move_group",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/taskstats.c:taskstats_user_cmd",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:oom_adj_write",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "drivers/tty/tty_audit.c:tty_audit_push_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431328,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443728,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1209",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:k_getrusage",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/taskstats.c:taskstats_user_cmd",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443728,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464096,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1215",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:k_getrusage",
        "kernel/sched/auto_group.c:proc_sched_autogroup_show_task",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice",
        "kernel/sched/auto_group.c:sched_autogroup_fork",
        "kernel/sched/auto_group.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464096,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452576,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1233",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452576,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480896,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1234",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480896,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497136,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1242",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497136,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530608,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1325",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530608,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548064,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1363",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548064,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574192,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574192,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579609800,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "fs/coredump.c:zap_threads",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609456,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590023,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1369",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:handle_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "fs/coredump.c:zap_threads",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589680,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579597191,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1371",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "fs/coredump.c:zap_threads",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596848,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672071,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1382",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "fs/coredump.c:zap_threads",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671680,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579769072,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1383",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_unfreeze_traced",
        "kernel/sys.c:getrusage",
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768640,
      "name": "__lock_task_sighand",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900944,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1384",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_unfreeze_traced",
        "kernel/sys.c:getrusage",
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:autogroup_move_group",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900464,
      "name": "__lock_task_sighand",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579950633,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1390",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_unfreeze_traced",
        "kernel/sys.c:getrusage",
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:autogroup_move_group",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950144,
      "name": "__lock_task_sighand",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579989897,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1391",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_unfreeze_traced",
        "kernel/sched/build_utility.c:proc_sched_autogroup_show_task",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice",
        "kernel/sched/build_utility.c:sched_autogroup_fork",
        "kernel/sched/build_utility.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989408,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490736544,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:taskstats_user_cmd",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490736544,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224788904,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:taskstats_user_cmd",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224788904,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283560368,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:taskstats_user_cmd",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283560368,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271445252,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "kernel/taskstats.c:taskstats_user_cmd",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271445252,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550496,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550496,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479216,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479216,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547776,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547776,
      "name": "__lock_task_sighand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct sighand_struct * __lock_task_sighand(struct task_struct * tsk, long unsigned int * flags)
```

```json
{
  "name": "__lock_task_sighand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580832,
      "name": "__lock_task_sighand",
      "external": true,
      "loc": "kernel/signal.c:1368",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:do_send_sig_info",
        "kernel/sys.c:getrusage",
        "kernel/sched/autogroup.c:proc_sched_autogroup_show_task",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice",
        "kernel/sched/autogroup.c:sched_autogroup_fork",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/freezer.c:freeze_task",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/cgroup/freezer.c:cgroup_freeze_task",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_pid_limits",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580832,
      "name": "__lock_task_sighand",
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
