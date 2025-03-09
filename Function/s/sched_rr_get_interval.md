# Function: <code>sched_rr_get_interval</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587440,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5101",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:compat_SyS_sched_rr_get_interval",
        "kernel/sched/core.c:SyS_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587440,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618656,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5226",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__x32_compat_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__ia32_compat_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618656,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579656064,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5209",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__x32_compat_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__ia32_compat_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656064,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679616,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5662",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679616,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719392,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719392,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761840,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:6086",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761840,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579750304,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:6906",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750304,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757424,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:7257",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757424,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579843232,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:8455",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843232,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579958048,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:8746",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958048,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117456,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:8930",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117456,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178960,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:9087",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178960,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580226727,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:9082",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226320,
      "name": "sched_rr_get_interval.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490902048,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__arm64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__arm64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490902048,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224916332,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224916332,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283741488,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283741488,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271565348,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695584,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695584,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624096,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624096,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690352,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690352,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```

```json
{
  "name": "sched_rr_get_interval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579727168,
      "name": "sched_rr_get_interval",
      "external": false,
      "loc": "kernel/sched/core.c:5853",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32",
        "kernel/sched/core.c:__ia32_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__x64_sys_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727168,
      "name": "sched_rr_get_interval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec * t)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * t</code> ➡️ <code>struct timespec64 * t</code>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 * t)
```
</details>
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
