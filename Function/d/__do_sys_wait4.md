# Function: <code>__do_sys_wait4</code>

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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579451552,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1673",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451552,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579485248,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1675",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485248,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503200,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1679",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503200,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529280,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529280,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559824,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1629",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559824,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540960,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1654",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540960,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545104,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1701",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545104,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617584,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1701",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617584,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711200,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1705",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711200,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837328,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1799",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837328,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886352,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1804",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886352,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924928,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1807",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924928,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490672184,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__arm64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490672184,
      "name": "__do_sys_wait4",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224744440,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__se_sys_wait4"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283495264,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__se_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283495264,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271410830,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__se_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271410830,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502944,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502944,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431808,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431808,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502864,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502864,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```

```json
{
  "name": "__do_sys_wait4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535504,
      "name": "__do_sys_wait4",
      "external": false,
      "loc": "kernel/exit.c:1625",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__ia32_sys_wait4",
        "kernel/exit.c:__x64_sys_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535504,
      "name": "__do_sys_wait4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
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
long int __do_sys_wait4(pid_t upid, int * stat_addr, int options, struct rusage * ru)
```
</details>
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
