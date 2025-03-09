# Function: <code>put_old_timespec32</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009696,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:862",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__x32_compat_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__ia32_compat_sys_sched_rr_get_interval",
        "kernel/time/posix-timers.c:__x32_compat_sys_clock_getres",
        "kernel/time/posix-timers.c:__ia32_compat_sys_clock_getres",
        "kernel/time/posix-timers.c:__x32_compat_sys_clock_gettime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_clock_gettime",
        "fs/select.c:poll_select_copy_remaining",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009696,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053008,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:940",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053008,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580102064,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102064,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163920,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:851",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163920,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580148064,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:851",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148064,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580152736,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:851",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152736,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580297264,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:851",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297264,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506432,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:851",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/hrtimer.c:nanosleep_copyout",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506432,
      "name": "put_old_timespec32",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760144,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:851",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/hrtimer.c:nanosleep_copyout",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760144,
      "name": "put_old_timespec32",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842816,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:851",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/hrtimer.c:nanosleep_copyout",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842816,
      "name": "put_old_timespec32",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932208,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:968",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/hrtimer.c:nanosleep_copyout",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932208,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491313952,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__arm64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__arm64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__arm64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491313952,
      "name": "put_old_timespec32",
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225308236,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__se_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__se_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225308236,
      "name": "put_old_timespec32",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284237280,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__se_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__se_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284237280,
      "name": "put_old_timespec32",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820186,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820186,
      "name": "put_old_timespec32",
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071264,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071264,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016080,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016080,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062336,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062336,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```

```json
{
  "name": "put_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580113104,
      "name": "put_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:941",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_getres_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_gettime32",
        "fs/select.c:poll_select_finish",
        "net/socket.c:__sys_recvmmsg",
        "net/core/sock.c:sock_gettstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113104,
      "name": "put_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int put_old_timespec32(const struct timespec64 * ts, void * uts)
```
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
