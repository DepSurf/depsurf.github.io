# Function: <code>nanosleep_copyout</code>

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
int nanosleep_copyout(struct restart_block * restart, struct timespec * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579893536,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1443",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893536,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579938064,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1448",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938064,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985664,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1659",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985664,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580032320,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1649",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032320,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580075664,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1649",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075664,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580124848,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124848,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580185792,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1851",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185792,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580170704,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170704,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580175232,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175232,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580320720,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2016",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320720,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580532208,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2016",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532208,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788560,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2016",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788560,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871808,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2019",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871808,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962304,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2020",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962304,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491344680,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491344680,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225337924,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225337924,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284275184,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284275184,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271840390,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271840390,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580094048,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094048,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580039376,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039376,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580085120,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085120,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec64 * ts)
```

```json
{
  "name": "nanosleep_copyout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580136832,
      "name": "nanosleep_copyout",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1846",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136832,
      "name": "nanosleep_copyout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int nanosleep_copyout(struct restart_block * restart, struct timespec * ts)
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
