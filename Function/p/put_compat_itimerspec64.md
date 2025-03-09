# Function: <code>put_compat_itimerspec64</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int put_compat_itimerspec64(const struct itimerspec * its, struct compat_itimerspec * uits)
```

```json
{
  "name": "put_compat_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025872,
      "name": "put_compat_itimerspec64",
      "external": true,
      "loc": "kernel/compat.c:422",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_settime",
        "kernel/time/posix-timers.c:compat_SyS_timer_gettime",
        "fs/timerfd.c:compat_SyS_timerfd_gettime",
        "fs/timerfd.c:compat_SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025872,
      "name": "put_compat_itimerspec64",
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
int put_compat_itimerspec64(const struct itimerspec * its, struct compat_itimerspec * uits)
```

```json
{
  "name": "put_compat_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072768,
      "name": "put_compat_itimerspec64",
      "external": true,
      "loc": "kernel/compat.c:381",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_settime",
        "kernel/time/posix-timers.c:compat_SyS_timer_gettime",
        "fs/timerfd.c:compat_SyS_timerfd_gettime",
        "fs/timerfd.c:compat_SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072768,
      "name": "put_compat_itimerspec64",
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
int put_compat_itimerspec64(const struct itimerspec64 * its, struct compat_itimerspec * uits)
```

```json
{
  "name": "put_compat_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132464,
      "name": "put_compat_itimerspec64",
      "external": true,
      "loc": "kernel/compat.c:346",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_settime",
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_gettime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_gettime",
        "fs/timerfd.c:__x32_compat_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_compat_sys_timerfd_gettime",
        "fs/timerfd.c:__x32_compat_sys_timerfd_settime",
        "fs/timerfd.c:__ia32_compat_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132464,
      "name": "put_compat_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int put_compat_itimerspec64(const struct itimerspec * its, struct compat_itimerspec * uits)
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
<code>const struct itimerspec * its</code> ➡️ <code>const struct itimerspec64 * its</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int put_compat_itimerspec64(const struct itimerspec64 * its, struct compat_itimerspec * uits)
```
</details>
</li>
</ul>
