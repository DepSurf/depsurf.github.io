# Function: <code>do_send_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct siginfo * info, struct task_struct * p, bool group)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431472,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1134",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:send_sig",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:kdb_send_sig_info",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigurg",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431472,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int do_send_sig_info(int sig, struct siginfo * info, struct task_struct * p, bool group)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443872,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1134",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443872,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int do_send_sig_info(int sig, struct siginfo * info, struct task_struct * p, bool group)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464240,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1140",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464240,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int do_send_sig_info(int sig, struct siginfo * info, struct task_struct * p, bool group)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452720,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1154",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452720,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int do_send_sig_info(int sig, struct siginfo * info, struct task_struct * p, bool group)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481040,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1155",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481040,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int do_send_sig_info(int sig, struct siginfo * info, struct task_struct * p, bool group)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497248,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1163",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497248,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530720,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1246",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530720,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555600,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555600,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581744,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581744,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617248,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__kill_pgrp_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617248,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597520,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1284",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_pid_info",
        "kernel/signal.c:__kill_pgrp_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597520,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602992,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1286",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_pid_info",
        "kernel/signal.c:__kill_pgrp_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602992,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678144,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1287",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_pid_info",
        "kernel/signal.c:__kill_pgrp_info",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678144,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772192,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1288",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__kill_pgrp_info",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772192,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904240,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1289",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__kill_pgrp_info",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904240,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953968,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1293",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__kill_pgrp_info",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953968,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993264,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1293",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__kill_pgrp_info",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993264,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490745144,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490745144,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224795940,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224795940,
      "name": "do_send_sig_info",
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283569648,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283569648,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271450298,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271450298,
      "name": "do_send_sig_info",
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558048,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558048,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486704,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486704,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555328,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555328,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int do_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "do_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588592,
      "name": "do_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1283",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig",
        "kernel/signal.c:group_send_sig_info",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory-failure.c:kill_procs",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio_to_task",
        "fs/fcntl.c:send_sigio_to_task",
        "drivers/tty/sysrq.c:send_sig_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588592,
      "name": "do_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pid_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>bool group</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct siginfo * info</code> ➡️ <code>struct kernel_siginfo * info</code>
</li>
</ul>
</details>
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
