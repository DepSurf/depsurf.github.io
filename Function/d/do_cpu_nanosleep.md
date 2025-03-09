# Function: <code>do_cpu_nanosleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, struct timespec * rqtp, struct itimerspec * it)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579841600,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1295",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579841600,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, struct timespec * rqtp, struct itimerspec * it)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870544,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1266",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870544,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, struct timespec * rqtp, struct itimerspec * it)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926224,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1262",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926224,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579935024,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1233",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935024,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980528,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1232",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980528,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031632,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1249",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031632,
      "name": "do_cpu_nanosleep.isra.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580078512,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1247",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078512,
      "name": "do_cpu_nanosleep.isra.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580122112,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1246",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122112,
      "name": "do_cpu_nanosleep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580171328,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171328,
      "name": "do_cpu_nanosleep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235392,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1198",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:process_cpu_nsleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235392,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220064,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1364",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:process_cpu_nsleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220064,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580225248,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1364",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:process_cpu_nsleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225248,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580373680,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1436",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:process_cpu_nsleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580373680,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589008,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1443",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:process_cpu_nsleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589008,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850992,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1443",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:process_cpu_nsleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850992,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934688,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1501",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:process_cpu_nsleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934688,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025712,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1501",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:process_cpu_nsleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025712,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491393176,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491393176,
      "name": "do_cpu_nanosleep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225391112,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225391112,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284335872,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284335872,
      "name": "do_cpu_nanosleep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271875156,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271875156,
      "name": "do_cpu_nanosleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580140528,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140528,
      "name": "do_cpu_nanosleep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580085936,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085936,
      "name": "do_cpu_nanosleep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580131600,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131600,
      "name": "do_cpu_nanosleep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_cpu_nanosleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580183344,
      "name": "do_cpu_nanosleep",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1219",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart",
        "kernel/time/posix-cpu-timers.c:posix_cpu_nsleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183344,
      "name": "do_cpu_nanosleep.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
<code>struct itimerspec * it</code>
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
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec * rqtp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 * rqtp)
```
</details>
</li>
</ul>
