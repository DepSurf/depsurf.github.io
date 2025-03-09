# Function: <code>task_tgid_nr_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pid_t task_tgid_nr_ns(struct task_struct * tsk, struct pid_namespace * ns)
```

```json
{
  "name": "task_tgid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491568,
      "name": "task_tgid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:539",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__send_signal",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
        "kernel/auditsc.c:audit_filter_rules",
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
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/self.c:proc_self_readlink",
        "fs/proc/self.c:proc_self_follow_link",
        "fs/proc/thread_self.c:proc_thread_self_readlink",
        "fs/proc/thread_self.c:proc_thread_self_follow_link",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491568,
      "name": "task_tgid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
pid_t task_tgid_nr_ns(struct task_struct * tsk, struct pid_namespace * ns)
```

```json
{
  "name": "task_tgid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505488,
      "name": "task_tgid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:539",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__send_signal",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
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
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/self.c:proc_self_readlink",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_readlink",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505488,
      "name": "task_tgid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
pid_t task_tgid_nr_ns(struct task_struct * tsk, struct pid_namespace * ns)
```

```json
{
  "name": "task_tgid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526160,
      "name": "task_tgid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:539",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__send_signal",
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process",
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
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/self.c:proc_self_get_link",
        "fs/proc/thread_self.c:proc_thread_self_get_link",
        "ipc/mqueue.c:__do_notify",
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526160,
      "name": "task_tgid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579449857,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010494,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580113867,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580133012,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580235880,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580236972,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580550717,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581793126,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808391,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808869,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560557,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867639,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579478259,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580057374,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580166411,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580185440,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580287080,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580288172,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942501,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581957943,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958421,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713005,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583024599,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1203",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494597,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580114200,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580226301,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580245274,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580348324,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580349402,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127877,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143103,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143569,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909727,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583225146,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1295",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579528093,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580161192,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580278695,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580299439,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580404388,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580405466,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222357,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582237727,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238193,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018269,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583342218,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1297",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547676,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580207264,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328672,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580351746,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580457301,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458395,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387918,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402175,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402625,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583199571,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583529721,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1369",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579573804,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580255600,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580377472,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580400514,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580506264,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580507307,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582486830,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582501135,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582501585,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305363,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583635609,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579608118,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325387,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453247,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580478085,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580593180,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580593798,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027704,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786010,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582802591,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582803047,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583636554,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583993026,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1404",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579588294,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580310779,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580441795,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580466280,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580582348,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582966,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034776,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860073,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876225,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876700,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758716,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584112642,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1463",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579595454,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314155,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580445875,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580470045,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580585005,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580585910,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581046354,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582888297,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582904559,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582905015,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782844,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584140102,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1485",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579666805,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580467691,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610787,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580636986,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580755833,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756747,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581269266,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221741,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238815,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583239271,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145068,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523894,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1583",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579766253,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661215,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580816305,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_task_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580846365,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_uring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971036,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972127,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561251,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719617,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583737823,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583738295,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584745852,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585162801,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1595",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579897810,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931071,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102641,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_task_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133197,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_uring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266828,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267951,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933491,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331521,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584351295,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584351815,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585440524,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585888929,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1617",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579947034,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017478,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194321,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_task_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223021,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_uring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361980,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363103,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116665,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584561708,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584581631,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584582151,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585671251,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586120817,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1626",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579986426,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113350,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300594,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_task_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329101,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_uring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581468204,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469378,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582257001,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584793394,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584812847,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584813447,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585918035,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586370113,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/pid.h:285",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490736256,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491499056,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491643188,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491663184,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491785036,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491786100,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494110188,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494125680,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494126124,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495044972,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495423316,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224788620,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 3225480228,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3225595176,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225620828,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225732416,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 3225733708,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 3227559464,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3227575060,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3227575584,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3228449756,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    },
    {
      "addr": 3228792996,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283559992,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284457480,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284639468,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284666776,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284833248,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284834664,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287779308,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287799036,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287799692,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288935504,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289461596,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271444996,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271940498,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272038310,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272055158,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272099928,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272100884,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273593668,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273607708,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273608118,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274319426,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274618632,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579550108,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580224400,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580346272,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580369314,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580475064,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580476107,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582455566,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582469871,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582470321,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583274099,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583604345,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579478828,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580171834,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293440,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580316482,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580422088,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580423150,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392809,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582407103,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582407553,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583211235,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583541401,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547388,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215872,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580337520,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580360562,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580466312,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580467355,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582446046,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582460351,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582460801,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258131,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583588121,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
  "name": "task_tgid_nr_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579580405,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580268567,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392736,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580418357,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580521989,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523040,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526318,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582540703,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541153,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_thread_self_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583354045,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685209,
      "name": "task_tgid_nr_ns",
      "external": false,
      "loc": "include/linux/sched.h:1363",
      "file": "security/tomoyo/realpath.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_get_local_path"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
pid_t task_tgid_nr_ns(struct task_struct * tsk, struct pid_namespace * ns)
```
</details>
</li>
</ul>
