# Function: <code>__do_compat_sys_wait4</code>

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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579451824,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1700",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451824,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579485520,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1702",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485520,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503472,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1706",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503472,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529552,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1652",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529552,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560096,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1656",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560096,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541232,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1681",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541232,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545376,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1728",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545376,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617856,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1728",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x64_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617856,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711584,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1732",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711584,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837792,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1826",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837792,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886816,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1831",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886816,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925392,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1834",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925392,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490672680,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1652",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__arm64_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490672680,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283495520,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1652",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__se_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283495520,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503216,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1652",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503216,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432080,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1652",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432080,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503136,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1652",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503136,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535776,
      "name": "__do_compat_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1652",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__x32_compat_sys_wait4",
        "kernel/exit.c:__ia32_compat_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535776,
      "name": "__do_compat_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t * stat_addr, int options, struct compat_rusage * ru)
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
