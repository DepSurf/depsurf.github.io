# Function: <code>find_vpid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491104,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:380",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpgid",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:f_setown",
        "fs/fcntl.c:SyS_fcntl",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_get",
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491104,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505270,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:380",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:SYSC_kill",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505024,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579525942,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:380",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:SYSC_kill",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525696,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513624,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:SYSC_kill",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513376,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579540981,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:250",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:SYSC_kill",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540912,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568661,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:262",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_kill",
        "kernel/signal.c:__do_sys_kill",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568576,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579605733,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:264",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605664,
      "name": "find_vpid",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629657,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629584,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579655209,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655136,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579686400,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:314",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tiocspgrp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686016,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664843,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:315",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664144,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671787,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:315",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670960,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749339,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:315",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748624,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858255,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:315",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853008,
      "name": "find_vpid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999439,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:315",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993712,
      "name": "find_vpid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048864,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:318",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047536,
      "name": "find_vpid",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091360,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:318",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090032,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490828360,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__arm64_sys_kill",
        "kernel/signal.c:__arm64_sys_kill",
        "kernel/sys.c:__arm64_sys_setpgid",
        "kernel/sys.c:__arm64_sys_getpriority",
        "kernel/sys.c:__arm64_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__arm64_sys_ioprio_get",
        "block/ioprio.c:__arm64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490828264,
      "name": "find_vpid",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224859872,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:__se_sys_kill",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/pid.c:find_get_pid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859872,
      "name": "find_vpid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283662608,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:__se_sys_kill",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283662480,
      "name": "find_vpid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271500436,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:__se_sys_kill",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:__se_sys_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271500350,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579631529,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631456,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579559865,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559792,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628793,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628720,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid * find_vpid(int nr)
```

```json
{
  "name": "find_vpid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662339,
      "name": "find_vpid",
      "external": true,
      "loc": "kernel/pid.c:267",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:kill_something_info",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662144,
      "name": "find_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
