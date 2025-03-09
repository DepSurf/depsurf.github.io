# Function: <code>compat_get_timespec64</code>

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
int compat_get_timespec64(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580026032,
      "name": "compat_get_timespec64",
      "external": true,
      "loc": "kernel/compat.c:149",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:compat_SyS_nanosleep",
        "kernel/time/posix-timers.c:compat_SyS_clock_nanosleep",
        "kernel/time/posix-timers.c:compat_SyS_clock_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026032,
      "name": "compat_get_timespec64",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timespec64(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580072928,
      "name": "compat_get_timespec64",
      "external": true,
      "loc": "kernel/compat.c:149",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:compat_SyS_nanosleep",
        "kernel/time/posix-timers.c:compat_SyS_clock_nanosleep",
        "kernel/time/posix-timers.c:compat_SyS_clock_settime",
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_pselect6",
        "fs/utimes.c:compat_SyS_utimensat",
        "fs/utimes.c:compat_SyS_utimensat",
        "fs/aio.c:compat_SyS_io_getevents",
        "ipc/sem.c:compat_SyS_semtimedop",
        "ipc/mqueue.c:compat_SyS_mq_timedreceive",
        "ipc/mqueue.c:compat_SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072928,
      "name": "compat_get_timespec64",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timespec64(struct timespec64 * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579963024,
      "name": "compat_get_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:915",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__x32_compat_sys_nanosleep",
        "kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep",
        "kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep",
        "kernel/time/posix-timers.c:__x32_compat_sys_clock_settime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_clock_settime",
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
        "ipc/mqueue.c:__ia32_compat_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963024,
      "name": "compat_get_timespec64",
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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int compat_get_timespec64(struct timespec * ts, const void * uts)
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int compat_get_timespec64(struct timespec64 * ts, const void * uts)
```
</details>
</li>
</ul>
