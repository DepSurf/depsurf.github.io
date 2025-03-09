# Function: <code>task_cputime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579378939,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429179,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579571873,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837624,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943565,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580152217,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581365317,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581374819,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2041",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_prstatus"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579391299,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441595,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579582769,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871748,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974381,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580186527,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552358,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581555811,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2183",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_prstatus"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579411653,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461963,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579608945,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579927428,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580004861,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580227135,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637518,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581640883,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched.h:2268",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_prstatus"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399505,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450466,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579586545,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579936256,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012059,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580234822,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580237009,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689099,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581701617,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:24",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579427553,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478866,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617409,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981744,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058923,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580286022,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580288209,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834699,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581847296,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579442591,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579495065,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647793,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032656,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116014,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580344773,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580347324,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580350043,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008029,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582022638,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579476111,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579528599,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685361,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580079536,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580163006,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580400645,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580403388,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580406107,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095917,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582110718,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494060,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553347,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719143,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123072,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580209060,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453413,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456288,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580459035,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264012,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582278748,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579520057,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579491,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761575,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580172558,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257396,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580502373,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580505248,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580507947,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363394,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582377828,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579549399,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579614859,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795189,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580237070,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326020,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580588485,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580591067,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580594443,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640654,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_prstatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657408,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_prstatus"
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579530615,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579595123,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784257,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221789,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311510,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580577765,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580219,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583611,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582711795,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_prstatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582727157,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_prstatus"
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579534855,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579600755,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792369,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580226957,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314880,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580645,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582747,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586555,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742089,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582756275,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579607271,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675747,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888129,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580375437,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468416,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751448,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:delayacct_add_tsk",
        "kernel/delayacct.c:delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580752951,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580757387,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583068969,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083187,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579700144,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779309,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580088340,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_cputime_adjusted",
        "kernel/sched/build_policy.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580592449,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661926,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580965896,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:delayacct_add_tsk",
        "kernel/delayacct.c:delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968008,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972873,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583547119,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561840,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579825552,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912045,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580260532,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_cputime_adjusted",
        "kernel/sched/build_policy.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854833,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931854,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581261272,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:delayacct_add_tsk",
        "kernel/delayacct.c:delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263688,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268732,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147759,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164288,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579874612,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961837,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326596,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_cputime_adjusted",
        "kernel/sched/build_policy.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938625,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018254,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356344,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:delayacct_add_tsk",
        "kernel/delayacct.c:delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358840,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363884,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584375022,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584392192,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:16",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool task_cputime(struct task_struct * t, u64 * utime, u64 * stime)
```

```json
{
  "name": "task_cputime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580428560,
      "name": "task_cputime",
      "external": true,
      "loc": "kernel/sched/cputime.c:850",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/sched/build_policy.c:task_cputime_adjusted",
        "kernel/sched/build_policy.c:thread_group_cputime",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample",
        "kernel/acct.c:acct_collect",
        "kernel/delayacct.c:delayacct_add_tsk",
        "kernel/delayacct.c:delayacct_add_tsk",
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580428560,
      "name": "task_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490658448,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490742432,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490940016,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491394720,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491499920,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491780720,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491783976,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491786588,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493958480,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493973100,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224733856,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3224793052,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3224958596,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 3225392864,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 3225481628,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 3225727972,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 3225731472,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3225734512,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 3227420752,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227424020,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf_fdpic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf_fdpic.c:fill_prstatus"
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283482148,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283566492,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283795744,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284337700,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284459508,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284827924,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284832108,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284835324,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287600256,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287615664,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271403168,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271448108,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271571812,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271876450,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271941868,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272096646,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272099198,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272101308,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273486822,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579493721,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555795,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579737495,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580141758,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580226196,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580471173,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474048,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580476747,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582332130,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582346564,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void task_cputime(struct task_struct * t, u64 * utime, u64 * stime)
```

```json
{
  "name": "task_cputime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579667136,
      "name": "task_cputime",
      "external": true,
      "loc": "kernel/sched/cputime.c:862",
      "file": "kernel/sched/cputime.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/acct.c:acct_collect",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667136,
      "name": "task_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579493641,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553075,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579721943,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580132830,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580217668,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580462421,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580465296,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580467995,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582322610,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582337044,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_cputime",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579526179,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579586312,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769319,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580184734,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270420,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518085,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520965,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580523691,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401877,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582416444,
      "name": "task_cputime",
      "external": false,
      "loc": "include/linux/sched/cputime.h:25",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
bool task_cputime(struct task_struct * t, u64 * utime, u64 * stime)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
void task_cputime(struct task_struct * t, u64 * utime, u64 * stime)
```
</details>
</li>
</ul>
