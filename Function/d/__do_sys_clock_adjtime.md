# Function: <code>__do_sys_clock_adjtime</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018496,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1084",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018496,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065552,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1050",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065552,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117520,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1055",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117520,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166848,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166848,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580228496,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1112",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228496,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212752,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1112",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212752,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215552,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1112",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215552,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580363184,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1112",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363184,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581568,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1121",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581568,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842944,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1121",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842944,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926384,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1162",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926384,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016992,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1162",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016992,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491387880,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491387880,
      "name": "__do_sys_clock_adjtime",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225384028,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225384028,
      "name": "__do_sys_clock_adjtime",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284329200,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284329200,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271871008,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271871008,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136048,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136048,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081328,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081328,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127120,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127120,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * utx)
```

```json
{
  "name": "__do_sys_clock_adjtime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178992,
      "name": "__do_sys_clock_adjtime",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1090",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178992,
      "name": "__do_sys_clock_adjtime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct timex * utx)
```
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
<code>struct timex * utx</code> ➡️ <code>struct __kernel_timex * utx</code>
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
