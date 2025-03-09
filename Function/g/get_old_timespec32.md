# Function: <code>get_old_timespec32</code>

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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009552,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:853",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__x32_compat_sys_nanosleep",
        "kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep",
        "kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x32_compat_sys_clock_settime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_clock_settime",
        "kernel/futex.c:__x32_compat_sys_futex",
        "kernel/futex.c:__ia32_compat_sys_futex",
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__x32_compat_sys_utimensat",
        "fs/utimes.c:__x32_compat_sys_utimensat",
        "fs/utimes.c:__ia32_compat_sys_utimensat",
        "fs/utimes.c:__ia32_compat_sys_utimensat",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__x32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_compat_sys_io_getevents",
        "ipc/mqueue.c:__x32_compat_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive",
        "ipc/mqueue.c:__x32_compat_sys_mq_timedsend",
        "ipc/mqueue.c:__ia32_compat_sys_mq_timedsend",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009552,
      "name": "get_old_timespec32",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580052848,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:931",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052848,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580101904,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101904,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163760,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:842",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163760,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580147904,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:842",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147904,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580152592,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:842",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152592,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580297120,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:842",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x64_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__x64_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297120,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506544,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:842",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex/syscalls.c:__ia32_sys_futex_time32",
        "kernel/futex/syscalls.c:__x64_sys_futex_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506544,
      "name": "get_old_timespec32",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760272,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:842",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex/syscalls.c:__ia32_sys_futex_time32",
        "kernel/futex/syscalls.c:__x64_sys_futex_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760272,
      "name": "get_old_timespec32",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842944,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:842",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex/syscalls.c:__ia32_sys_futex_time32",
        "kernel/futex/syscalls.c:__x64_sys_futex_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842944,
      "name": "get_old_timespec32",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932336,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:949",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex/syscalls.c:__ia32_sys_futex_time32",
        "kernel/futex/syscalls.c:__x64_sys_futex_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932336,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491313672,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__arm64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__arm64_sys_clock_settime32",
        "kernel/futex.c:__arm64_sys_futex_time32",
        "fs/select.c:__arm64_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__arm64_sys_utimensat_time32",
        "fs/utimes.c:__arm64_sys_utimensat_time32",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_getevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__arm64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__arm64_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491313672,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225308980,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__se_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__se_sys_clock_settime32",
        "kernel/futex.c:__se_sys_futex_time32",
        "fs/select.c:__se_sys_ppoll_time32",
        "fs/select.c:do_pselect",
        "fs/utimes.c:__se_sys_utimensat_time32",
        "fs/utimes.c:__se_sys_utimensat_time32",
        "fs/aio.c:__se_sys_io_getevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__se_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__se_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225308980,
      "name": "get_old_timespec32",
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284238128,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__se_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__se_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__se_sys_clock_settime32",
        "kernel/futex.c:__se_sys_futex_time32",
        "fs/select.c:__se_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__se_sys_utimensat_time32",
        "fs/utimes.c:__se_sys_utimensat_time32",
        "fs/aio.c:__se_compat_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__se_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__se_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284238128,
      "name": "get_old_timespec32",
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820540,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820540,
      "name": "get_old_timespec32",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071104,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071104,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580015920,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015920,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062176,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062176,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "get_old_timespec32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112944,
      "name": "get_old_timespec32",
      "external": true,
      "loc": "kernel/time/time.c:932",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32",
        "kernel/time/posix-timers.c:__ia32_sys_clock_settime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_settime32",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112944,
      "name": "get_old_timespec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int get_old_timespec32(struct timespec64 * ts, const void * uts)
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
