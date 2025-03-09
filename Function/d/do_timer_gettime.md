# Function: <code>do_timer_gettime</code>

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
int do_timer_gettime(timer_t timer_id, struct itimerspec * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925072,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:716",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_gettime",
        "kernel/time/posix-timers.c:SyS_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925072,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int do_timer_gettime(timer_t timer_id, struct itimerspec * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970496,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:722",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:compat_SyS_timer_gettime",
        "kernel/time/posix-timers.c:SyS_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970496,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018304,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:731",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_gettime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_gettime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018304,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065360,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__x32_compat_sys_timer_gettime",
        "kernel/time/posix-timers.c:__ia32_compat_sys_timer_gettime",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065360,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109008,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109008,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158176,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158176,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220896,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:715",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220896,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580205152,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:715",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205152,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580210464,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:715",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210464,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357328,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:715",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357328,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572160,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:715",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572160,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832960,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:715",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832960,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916512,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:696",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916512,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007120,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:696",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007120,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491383512,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__arm64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491383512,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225377096,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__se_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225377096,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284320800,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__se_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284320800,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271869484,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__se_sys_timer_gettime"
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127376,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127376,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072672,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072672,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118448,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118448,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
```

```json
{
  "name": "do_timer_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170304,
      "name": "do_timer_gettime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:695",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime32",
        "kernel/time/posix-timers.c:__ia32_sys_timer_gettime",
        "kernel/time/posix-timers.c:__x64_sys_timer_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170304,
      "name": "do_timer_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int do_timer_gettime(timer_t timer_id, struct itimerspec * setting)
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
<code>struct itimerspec * setting</code> ➡️ <code>struct itimerspec64 * setting</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 * setting)
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
