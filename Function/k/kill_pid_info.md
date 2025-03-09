# Function: <code>kill_pid_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433072,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1288",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433072,
      "name": "kill_pid_info",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445488,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1288",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445488,
      "name": "kill_pid_info",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465856,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1294",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465856,
      "name": "kill_pid_info",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579454384,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1312",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454384,
      "name": "kill_pid_info",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482704,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1313",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482704,
      "name": "kill_pid_info",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499184,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1311",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499184,
      "name": "kill_pid_info",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532640,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1395",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532640,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556048,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1433",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556048,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582192,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582192,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579620134,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kill_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619440,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599776,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1439",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599776,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605280,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1441",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605280,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680560,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1467",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680560,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579775904,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1468",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kill_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775008,
      "name": "kill_pid_info",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579908352,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1469",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kill_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907376,
      "name": "kill_pid_info",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958080,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1475",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kill_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957104,
      "name": "kill_pid_info",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579997360,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1481",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kill_pid"
      ],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996384,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490745784,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal",
        "kernel/signal.c:__arm64_sys_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490745784,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224796452,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224796452,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283570384,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283570384,
      "name": "kill_pid_info",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271450722,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:kill_pid",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271450722,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558496,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558496,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487152,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487152,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555776,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555776,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int kill_pid_info(int sig, struct kernel_siginfo * info, struct pid * pid)
```

```json
{
  "name": "kill_pid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589072,
      "name": "kill_pid_info",
      "external": true,
      "loc": "kernel/signal.c:1438",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:kill_pid",
        "kernel/signal.c:kill_something_info",
        "kernel/time/itimer.c:it_real_fn",
        "ipc/mqueue.c:__do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589072,
      "name": "kill_pid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
