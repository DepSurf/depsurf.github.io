# Function: <code>get_itimerspec64</code>

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
int get_itimerspec64(struct itimerspec * it, const struct itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873248,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:922",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_settime",
        "fs/timerfd.c:SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873248,
      "name": "get_itimerspec64",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec * it, const struct itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916672,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_settime",
        "fs/timerfd.c:SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916672,
      "name": "get_itimerspec64",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 * it, const struct itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962048,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:933",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962048,
      "name": "get_itimerspec64",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 * it, const struct itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008816,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:871",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008816,
      "name": "get_itimerspec64",
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052432,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:949",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052432,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101488,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101488,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163504,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:860",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163504,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147648,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:860",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147648,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152336,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:860",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152336,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296864,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:860",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296864,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507584,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:860",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507584,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761408,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:860",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761408,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844080,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:860",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844080,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933472,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:984",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933472,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491313600,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_timer_settime",
        "fs/timerfd.c:__arm64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491313600,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225309364,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime",
        "fs/timerfd.c:__se_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225309364,
      "name": "get_itimerspec64",
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284238016,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime",
        "fs/timerfd.c:__se_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284238016,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820614,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime",
        "fs/timerfd.c:__se_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820614,
      "name": "get_itimerspec64",
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070688,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070688,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015504,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015504,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061760,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061760,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec64 * it, const struct __kernel_itimerspec * uit)
```

```json
{
  "name": "get_itimerspec64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112528,
      "name": "get_itimerspec64",
      "external": true,
      "loc": "kernel/time/time.c:950",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112528,
      "name": "get_itimerspec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int get_itimerspec64(struct itimerspec * it, const struct itimerspec * uit)
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
<code>struct itimerspec * it</code> ➡️ <code>struct itimerspec64 * it</code>
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
<code>const struct itimerspec * uit</code> ➡️ <code>const struct __kernel_itimerspec * uit</code>
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
