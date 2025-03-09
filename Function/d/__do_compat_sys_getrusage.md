# Function: <code>__do_compat_sys_getrusage</code>

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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534320,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1816",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534320,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570432,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1817",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570432,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593792,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1818",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593792,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619840,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1808",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619840,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650368,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1824",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650368,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630912,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1825",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630912,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637616,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1842",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637616,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714144,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1851",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x64_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714144,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815776,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1863",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815776,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951936,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1868",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951936,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580001696,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1886",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001696,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041232,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1899",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041232,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490786272,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1808",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490786272,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283611152,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1808",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283611152,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596144,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1808",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596144,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524784,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1808",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524784,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593424,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1808",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593424,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
```

```json
{
  "name": "__do_compat_sys_getrusage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627088,
      "name": "__do_compat_sys_getrusage",
      "external": false,
      "loc": "kernel/sys.c:1808",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__x32_compat_sys_getrusage",
        "kernel/sys.c:__ia32_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627088,
      "name": "__do_compat_sys_getrusage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
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
long int __do_compat_sys_getrusage(int who, struct compat_rusage * ru)
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
