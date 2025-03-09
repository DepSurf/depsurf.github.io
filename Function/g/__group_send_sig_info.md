# Function: <code>__group_send_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579429350,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1123",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430912,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579441766,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1123",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443312,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579462134,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1129",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463680,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579450632,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1143",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452160,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479023,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1144",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480480,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579495298,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496720,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579528808,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1241",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530192,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579553564,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1273",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552512,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579579708,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578640,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579615076,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614688,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579595340,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1279",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594928,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579600967,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1281",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600560,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675959,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1282",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675552,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490742712,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490741600,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224793264,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224792236,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283566768,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283565568,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271448288,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271447472,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579556012,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554944,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579484721,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483648,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579553292,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552224,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "__group_send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579586529,
      "name": "__group_send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1278",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585392,
      "name": "__group_send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```
</details>
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
