# Function: <code>__do_compat_sys_waitid</code>

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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446976,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1715",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446976,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480464,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1717",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480464,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498480,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1721",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498480,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524720,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1667",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524720,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556368,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1671",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556368,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537552,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1696",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537552,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541776,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1743",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541776,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614288,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1743",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x64_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614288,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707232,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1747",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707232,
      "name": "__do_compat_sys_waitid",
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579832864,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1841",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832864,
      "name": "__do_compat_sys_waitid",
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881872,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1846",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881872,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924176,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1849",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924176,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490665608,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1667",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__arm64_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490665608,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2068
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283488896,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1667",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__se_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283488896,
      "name": "__do_compat_sys_waitid",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498384,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1667",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498384,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579427264,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1667",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427264,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498304,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1667",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498304,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "__do_compat_sys_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530912,
      "name": "__do_compat_sys_waitid",
      "external": false,
      "loc": "kernel/exit.c:1667",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_waitid",
        "kernel/exit.c:__ia32_compat_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530912,
      "name": "__do_compat_sys_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
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
