# Function: <code>get_timespec64</code>

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
int get_timespec64(struct timespec * ts, const struct timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579873254,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:894",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:SyS_nanosleep",
        "kernel/time/posix-timers.c:SyS_clock_nanosleep",
        "kernel/time/posix-timers.c:SyS_clock_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873136,
      "name": "get_timespec64",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_timespec64(struct timespec * ts, const struct timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579916678,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:843",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:SyS_nanosleep",
        "kernel/time/posix-timers.c:SyS_clock_nanosleep",
        "kernel/time/posix-timers.c:SyS_clock_settime",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_pselect6",
        "fs/utimes.c:SyS_utimensat",
        "fs/utimes.c:SyS_utimensat",
        "fs/aio.c:SyS_io_getevents",
        "ipc/sem.c:SyS_semtimedop",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916560,
      "name": "get_timespec64",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_timespec64(struct timespec64 * ts, const struct timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962094,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:855",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:do_pselect",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961936,
      "name": "get_timespec64",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_timespec64(struct timespec64 * ts, const struct timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580008862,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:793",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008704,
      "name": "get_timespec64",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052288,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__do_sys_pselect6",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052288,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101344,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101344,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163360,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:781",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:io_timeout_prep",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163360,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147504,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:781",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_timeout_prep",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147504,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152192,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:781",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_timeout_prep",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152192,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296720,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:781",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x64_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/eventpoll.c:__x64_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/aio.c:__x64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_timeout_prep",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296720,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580507632,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:781",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/syscalls.c:__ia32_sys_futex",
        "kernel/futex/syscalls.c:__x64_sys_futex",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:__io_timeout_prep",
        "io_uring/io_uring.c:io_timeout_remove_prep",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505584,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580761456,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:781",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/syscalls.c:__ia32_sys_futex",
        "kernel/futex/syscalls.c:__x64_sys_futex",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/timeout.c:io_timeout_remove_prep",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759152,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580844128,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:781",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/syscalls.c:__ia32_sys_futex",
        "kernel/futex/syscalls.c:__x64_sys_futex",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/timeout.c:io_timeout_remove_prep",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841824,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580933520,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex/syscalls.c:futex2_setup_timeout",
        "kernel/futex/syscalls.c:__ia32_sys_futex",
        "kernel/futex/syscalls.c:__x64_sys_futex",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/timeout.c:io_timeout_remove_prep",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931216,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491313448,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__arm64_sys_nanosleep",
        "kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__arm64_sys_clock_settime",
        "kernel/futex.c:__arm64_sys_futex",
        "fs/select.c:__arm64_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__arm64_sys_ppoll",
        "fs/select.c:__arm64_sys_pselect6",
        "fs/utimes.c:__arm64_sys_utimensat",
        "fs/utimes.c:__arm64_sys_utimensat",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__arm64_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__arm64_sys_mq_timedreceive",
        "ipc/mqueue.c:__arm64_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491313448,
      "name": "get_timespec64",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225309172,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/posix-timers.c:__se_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__se_sys_clock_settime",
        "kernel/futex.c:__se_sys_futex",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:do_pselect",
        "fs/utimes.c:__se_sys_utimensat",
        "fs/utimes.c:__se_sys_utimensat",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225309172,
      "name": "get_timespec64",
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284237840,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__se_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__se_sys_nanosleep",
        "kernel/time/posix-timers.c:__se_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__se_sys_clock_settime",
        "kernel/futex.c:__se_sys_futex",
        "fs/select.c:__se_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_pselect6",
        "fs/utimes.c:__se_sys_utimensat",
        "fs/utimes.c:__se_sys_utimensat",
        "fs/aio.c:__se_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284237840,
      "name": "get_timespec64",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271820640,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64"
      ],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigtimedwait",
        "kernel/time/hrtimer.c:__se_sys_nanosleep",
        "kernel/time/posix-timers.c:__se_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__se_sys_clock_settime",
        "kernel/futex.c:__se_sys_futex",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_pselect6",
        "fs/utimes.c:__se_sys_utimensat",
        "fs/utimes.c:__se_sys_utimensat",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820466,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070544,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070544,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015360,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015360,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061616,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061616,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int get_timespec64(struct timespec64 * ts, const struct __kernel_timespec * uts)
```

```json
{
  "name": "get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112384,
      "name": "get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/time.c:get_itimerspec64",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "ipc/sem.c:ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112384,
      "name": "get_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int get_timespec64(struct timespec * ts, const struct timespec * uts)
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
<code>struct timespec * ts</code> ➡️ <code>struct timespec64 * ts</code>
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
<code>const struct timespec * uts</code> ➡️ <code>const struct __kernel_timespec * uts</code>
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
