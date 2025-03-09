# Function: <code>hrtimer_nanosleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int hrtimer_nanosleep(struct timespec * rqtp, struct timespec * rmtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827648,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1545",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:SyS_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_SyS_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827648,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int hrtimer_nanosleep(struct timespec * rqtp, struct timespec * rmtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855872,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1535",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:SyS_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_SyS_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855872,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int hrtimer_nanosleep(struct timespec * rqtp, struct timespec * rmtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884720,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1535",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:SyS_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_SyS_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884720,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893616,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1513",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:compat_SyS_nanosleep",
        "kernel/time/hrtimer.c:SyS_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893616,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
long int hrtimer_nanosleep(const struct timespec * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938144,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1518",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:compat_SyS_nanosleep",
        "kernel/time/hrtimer.c:SyS_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938144,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579985744,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1729",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__x32_compat_sys_nanosleep",
        "kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985744,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032400,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1719",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__x32_compat_sys_nanosleep",
        "kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032400,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075744,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1719",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075744,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124928,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124928,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185872,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep_timens",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185872,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170784,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1935",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep_timens",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170784,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580175312,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1935",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep_timens",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175312,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320800,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2083",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep_timens",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320800,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580532304,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2083",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep_timens",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532304,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788672,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2083",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep_timens",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788672,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871920,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2086",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep_timens",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871920,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962416,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2087",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep_timens",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962416,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491344800,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__arm64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__arm64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491344800,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225338028,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__se_sys_nanosleep_time32",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225338028,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284275328,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__se_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__se_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284275328,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271840460,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__se_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271840460,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094128,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094128,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039456,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039456,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085200,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085200,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
long int hrtimer_nanosleep(const struct timespec64 * rqtp, const enum hrtimer_mode mode, const clockid_t clockid)
```

```json
{
  "name": "hrtimer_nanosleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136912,
      "name": "hrtimer_nanosleep",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1913",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep_time32",
        "kernel/time/hrtimer.c:__ia32_sys_nanosleep",
        "kernel/time/hrtimer.c:__x64_sys_nanosleep",
        "kernel/time/posix-timers.c:common_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136912,
      "name": "hrtimer_nanosleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct timespec * rmtp</code>
</li>
<li>
<b>Param reordered. </b>
<code>rqtp, rmtp, mode, clockid</code> ➡️ <code>rqtp, mode, clockid</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct timespec * rqtp</code> ➡️ <code>const struct timespec * rqtp</code>
</li>
</ul>
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
<code>const struct timespec * rqtp</code> ➡️ <code>const struct timespec64 * rqtp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec64 * rqtp</code> ➡️ <code>ktime_t rqtp</code>
</li>
</ul>
</details>
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
