# Function: <code>pid_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491168,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:435",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:sys_setsid",
        "kernel/time/posix-timers.c:posix_timer_event",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491168,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505206,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:435",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/time/posix-timers.c:posix_timer_event",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505088,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579525878,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:435",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/time/posix-timers.c:posix_timer_event",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525760,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513558,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:436",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/time/posix-timers.c:posix_timer_event",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513440,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579540277,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:305",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid",
        "kernel/time/posix-timers.c:posix_timer_event",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540144,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579567941,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:317",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/time/posix-timers.c:posix_timer_event",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567824,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579605125,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:326",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_info_as_cred",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605008,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629932,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628944,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579655484,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654512,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579687090,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:395",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:pid_for_clock",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_jobctrl.c:tiocspgrp",
        "drivers/tty/tty_jobctrl.c:tiocspgrp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685584,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665362,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:396",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/exit.c:thread_group_exited",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:pid_for_clock",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663856,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672194,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:396",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/exit.c:thread_group_exited",
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_wait",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:pid_for_clock",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670656,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749490,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:396",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/exit.c:thread_group_exited",
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_wait",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:pid_for_clock",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748288,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579854061,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:396",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/exit.c:thread_group_exited",
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_wait",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:pid_for_clock",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852624,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579995005,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:396",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/exit.c:thread_group_exited",
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_wait",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:pid_for_clock",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993248,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049469,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:399",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/exit.c:thread_group_exited",
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_wait",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:pid_for_clock",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047072,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091965,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:399",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/exit.c:thread_group_exited",
        "kernel/exit.c:__do_wait",
        "kernel/exit.c:__do_wait",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:pid_for_clock",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/gpu/drm/drm_debugfs.c:drm_clients_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089568,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490828668,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__arm64_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__arm64_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490827432,
      "name": "pid_task",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224861980,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859212,
      "name": "pid_task",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283662772,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283661488,
      "name": "pid_task",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271502608,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271499522,
      "name": "pid_task",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579631804,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630816,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560140,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559168,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629068,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628096,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662849,
      "name": "pid_task",
      "external": true,
      "loc": "kernel/pid.c:329",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:get_pid_task",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:pidfd_poll",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:kill_pid_info",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_loginuid_write",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:get_children_pid",
        "fs/proc/fd.c:proc_fd_permission",
        "fs/proc/proc_net.c:get_proc_task_net",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661728,
      "name": "pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
