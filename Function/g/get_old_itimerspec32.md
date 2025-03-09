# Function: <code>get_old_itimerspec32</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008976,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:901",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_settime",
        "fs/timerfd.c:__x32_compat_sys_timerfd_settime",
        "fs/timerfd.c:__ia32_compat_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008976,
      "name": "get_old_itimerspec32",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052480,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:979",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052480,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101536,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101536,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164624,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:890",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164624,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148768,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:890",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148768,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153456,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:890",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153456,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580297984,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:890",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297984,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506832,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:890",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506832,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760592,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:890",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760592,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843264,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:890",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843264,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932656,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:1029",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932656,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491313800,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_timer_settime32",
        "fs/timerfd.c:__arm64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491313800,
      "name": "get_old_itimerspec32",
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225309420,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime32",
        "fs/timerfd.c:__se_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225309420,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284238272,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime32",
        "fs/timerfd.c:__se_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284238272,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820722,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820722,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070736,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070736,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015552,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015552,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061808,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061808,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
```

```json
{
  "name": "get_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112576,
      "name": "get_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:980",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112576,
      "name": "get_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int get_old_itimerspec32(struct itimerspec64 * its, const struct old_itimerspec32 * uits)
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
