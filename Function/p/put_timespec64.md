# Function: <code>put_timespec64</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec * ts, struct timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872870,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:911",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_clock_getres",
        "kernel/time/posix-timers.c:SyS_clock_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872768,
      "name": "put_timespec64",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec * ts, struct timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579916278,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:860",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/time/posix-timers.c:SyS_clock_getres",
        "kernel/time/posix-timers.c:SyS_clock_gettime",
        "fs/select.c:poll_select_copy_remaining"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916176,
      "name": "put_timespec64",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579961566,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:877",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_copy_remaining"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961424,
      "name": "put_timespec64",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580008046,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:815",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_copy_remaining",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007904,
      "name": "put_timespec64",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580051630,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:893",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051488,
      "name": "put_timespec64",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100686,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100544,
      "name": "put_timespec64",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580165432,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:804",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162880,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149576,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:804",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147024,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580154232,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:804",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151712,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580298760,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:804",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296240,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580507480,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:804",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/hrtimer.c:nanosleep_copyout",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505024,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580761288,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:804",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/hrtimer.c:nanosleep_copyout",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758544,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580843960,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:804",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/hrtimer.c:nanosleep_copyout",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841216,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580933352,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:902",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/hrtimer.c:nanosleep_copyout",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930608,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491315332,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__arm64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__arm64_sys_clock_getres",
        "kernel/time/posix-timers.c:__arm64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491314368,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225308428,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval",
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/posix-timers.c:__se_sys_clock_getres",
        "kernel/time/posix-timers.c:__se_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225308428,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284237476,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__se_sys_clock_getres",
        "kernel/time/posix-timers.c:__se_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284237136,
      "name": "put_timespec64",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271820284,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__se_sys_clock_getres",
        "kernel/time/posix-timers.c:__se_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820114,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580069886,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069744,
      "name": "put_timespec64",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580014702,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014560,
      "name": "put_timespec64",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580060958,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060816,
      "name": "put_timespec64",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int put_timespec64(const struct timespec64 * ts, struct __kernel_timespec * uts)
```

```json
{
  "name": "put_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580111726,
      "name": "put_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111584,
      "name": "put_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int put_timespec64(const struct timespec * ts, struct timespec * uts)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec * ts</code> ➡️ <code>const struct timespec64 * ts</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * uts</code> ➡️ <code>struct __kernel_timespec * uts</code>
</li>
</ul>
</details>
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
