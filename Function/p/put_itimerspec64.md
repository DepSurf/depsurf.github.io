# Function: <code>put_itimerspec64</code>

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
int put_itimerspec64(const struct itimerspec * it, struct itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872864,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:937",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_gettime",
        "fs/timerfd.c:SyS_timerfd_gettime",
        "fs/timerfd.c:SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872864,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec * it, struct itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916272,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:886",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_gettime",
        "fs/timerfd.c:SyS_timerfd_gettime",
        "fs/timerfd.c:SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916272,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec64 * it, struct itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961520,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:948",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961520,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec64 * it, struct itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008000,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:886",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008000,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051584,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:964",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051584,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100640,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100640,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165360,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:875",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165360,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149504,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:875",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149504,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580154160,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:875",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154160,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298688,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:875",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298688,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507408,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:875",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507408,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761216,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:875",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761216,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843888,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:875",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843888,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933280,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:1007",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933280,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491315280,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_timer_settime",
        "kernel/time/posix-timers.c:__arm64_sys_timer_gettime",
        "fs/timerfd.c:__arm64_sys_timerfd_gettime",
        "fs/timerfd.c:__arm64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491315280,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225308624,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime",
        "kernel/time/posix-timers.c:__se_sys_timer_gettime",
        "fs/timerfd.c:__se_sys_timerfd_gettime",
        "fs/timerfd.c:__se_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225308624,
      "name": "put_itimerspec64",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284237424,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime",
        "kernel/time/posix-timers.c:__se_sys_timer_gettime",
        "fs/timerfd.c:__se_sys_timerfd_gettime",
        "fs/timerfd.c:__se_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284237424,
      "name": "put_itimerspec64",
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820258,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime",
        "kernel/time/posix-timers.c:__se_sys_timer_gettime",
        "fs/timerfd.c:__se_sys_timerfd_gettime",
        "fs/timerfd.c:__se_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820258,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069840,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069840,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014656,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014656,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060912,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060912,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec64 * it, struct __kernel_itimerspec * uit)
```

```json
{
  "name": "put_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111680,
      "name": "put_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:965",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111680,
      "name": "put_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int put_itimerspec64(const struct itimerspec * it, struct itimerspec * uit)
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
<code>const struct itimerspec * it</code> ➡️ <code>const struct itimerspec64 * it</code>
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
<code>struct itimerspec * uit</code> ➡️ <code>struct __kernel_itimerspec * uit</code>
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
