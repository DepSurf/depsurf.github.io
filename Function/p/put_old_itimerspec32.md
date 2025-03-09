# Function: <code>put_old_itimerspec32</code>

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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008160,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:912",
      "file": "kernel/time/time.c",
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
      "addr": 18446744071580008160,
      "name": "put_old_itimerspec32",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051744,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:990",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051744,
      "name": "put_old_itimerspec32",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100800,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100800,
      "name": "put_old_itimerspec32",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164464,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:901",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164464,
      "name": "put_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148608,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:901",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148608,
      "name": "put_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153296,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:901",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153296,
      "name": "put_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580297824,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:901",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297824,
      "name": "put_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506672,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:901",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506672,
      "name": "put_old_itimerspec32",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760416,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:901",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760416,
      "name": "put_old_itimerspec32",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843088,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:901",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843088,
      "name": "put_old_itimerspec32",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932480,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:1048",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932480,
      "name": "put_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491316008,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__arm64_sys_timer_gettime32",
        "fs/timerfd.c:__arm64_sys_timerfd_gettime32",
        "fs/timerfd.c:__arm64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491316008,
      "name": "put_old_itimerspec32",
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225308680,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime32",
        "kernel/time/posix-timers.c:__se_sys_timer_gettime32",
        "fs/timerfd.c:__se_sys_timerfd_gettime32",
        "fs/timerfd.c:__se_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225308680,
      "name": "put_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284237632,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime32",
        "kernel/time/posix-timers.c:__se_sys_timer_gettime32",
        "fs/timerfd.c:__se_sys_timerfd_gettime32",
        "fs/timerfd.c:__se_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284237632,
      "name": "put_old_itimerspec32",
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820362,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820362,
      "name": "put_old_itimerspec32",
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070000,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070000,
      "name": "put_old_itimerspec32",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014816,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014816,
      "name": "put_old_itimerspec32",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061072,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061072,
      "name": "put_old_itimerspec32",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
```

```json
{
  "name": "put_old_itimerspec32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111840,
      "name": "put_old_itimerspec32",
      "external": true,
      "loc": "kernel/time/time.c:991",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111840,
      "name": "put_old_itimerspec32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int put_old_itimerspec32(const struct itimerspec64 * its, struct old_itimerspec32 * uits)
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
