# Function: <code>kernel_waitid</code>

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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403200,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1551",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:C_SYSC_waitid",
        "kernel/exit.c:C_SYSC_waitid",
        "kernel/exit.c:SYSC_waitid",
        "kernel/exit.c:SYSC_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403200,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431232,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1550",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:C_SYSC_waitid",
        "kernel/exit.c:C_SYSC_waitid",
        "kernel/exit.c:SYSC_waitid",
        "kernel/exit.c:SYSC_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431232,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446352,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1550",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446352,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479872,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1553",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479872,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497888,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1557",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497888,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523888,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523888,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555408,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1494",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555408,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536672,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1496",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536672,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540976,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1543",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540976,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613488,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1543",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613488,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706256,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1547",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706256,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831824,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1641",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831824,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880896,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1646",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880896,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923520,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1697",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923520,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490662872,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490662872,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224738704,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224738704,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283487232,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283487232,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271406674,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271406674,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497552,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497552,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426432,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426432,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497472,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497472,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```

```json
{
  "name": "kernel_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530080,
      "name": "kernel_waitid",
      "external": false,
      "loc": "kernel/exit.c:1490",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530080,
      "name": "kernel_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info * infop, int options, struct rusage * ru)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
