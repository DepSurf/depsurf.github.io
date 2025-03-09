# Function: <code>do_timer_settime</code>

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
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec * new_spec64, struct itimerspec * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925264,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:866",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925264,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec * new_spec64, struct itimerspec * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970688,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:872",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970688,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580021600,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:881",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021600,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580068656,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:847",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068656,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580111616,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:847",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111616,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161136,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160800,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580221739,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:898",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221408,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580206699,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:898",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205664,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580211309,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:898",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210976,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580358205,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:898",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357872,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572368,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:898",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572368,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833184,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:898",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833184,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916736,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:900",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916736,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007344,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:900",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007344,
      "name": "do_timer_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491384704,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__arm64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__arm64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__arm64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491384104,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225382644,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime32",
        "kernel/time/posix-timers.c:__se_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime32",
        "kernel/time/posix-timers.c:__se_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225379832,
      "name": "do_timer_settime.part.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284327904,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime32",
        "kernel/time/posix-timers.c:__se_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime32",
        "kernel/time/posix-timers.c:__se_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284325056,
      "name": "do_timer_settime.part.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271869780,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__se_sys_timer_settime"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580130336,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130000,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580075632,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075296,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121408,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121072,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
  "name": "do_timer_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580173264,
      "name": "do_timer_settime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:876",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_settime",
        "kernel/time/posix-timers.c:__x64_sys_timer_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172928,
      "name": "do_timer_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec * new_spec64, struct itimerspec * old_spec64)
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
<code>struct itimerspec * new_spec64</code> ➡️ <code>struct itimerspec64 * new_spec64</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct itimerspec * old_spec64</code> ➡️ <code>struct itimerspec64 * old_spec64</code>
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 * new_spec64, struct itimerspec64 * old_spec64)
```
</details>
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
