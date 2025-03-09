# Function: <code>compat_put_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958672,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:184",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_nanosleep_restart",
        "kernel/compat.c:compat_clock_nanosleep_restart",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_SyS_clock_gettime",
        "kernel/compat.c:compat_SyS_clock_getres",
        "kernel/compat.c:compat_SyS_clock_nanosleep",
        "kernel/compat.c:compat_SyS_sched_rr_get_interval",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958672,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988512,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:184",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_sched_rr_get_interval",
        "kernel/compat.c:compat_SyS_clock_nanosleep",
        "kernel/compat.c:compat_clock_nanosleep_restart",
        "kernel/compat.c:compat_SyS_clock_getres",
        "kernel/compat.c:compat_SyS_clock_gettime",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_nanosleep_restart",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988512,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019040,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:184",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_sched_rr_get_interval",
        "kernel/compat.c:compat_SyS_clock_nanosleep",
        "kernel/compat.c:compat_clock_nanosleep_restart",
        "kernel/compat.c:compat_SyS_clock_getres",
        "kernel/compat.c:compat_SyS_clock_gettime",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_nanosleep_restart",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019040,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580026624,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:194",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_sched_rr_get_interval",
        "net/socket.c:compat_sock_ioctl",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026624,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073584,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:194",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073584,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132912,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:151",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132912,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580180112,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:151",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180112,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580226144,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:84",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226144,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580274368,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:84",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274368,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491514680,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:84",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491514680,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284483616,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:84",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284483616,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580243168,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:84",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243168,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580190720,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:84",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190720,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580234416,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:84",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234416,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
```

```json
{
  "name": "compat_put_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580287408,
      "name": "compat_put_timespec",
      "external": true,
      "loc": "kernel/compat.c:84",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287408,
      "name": "compat_put_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int compat_put_timespec(const struct timespec * ts, void * uts)
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
int compat_put_timespec(const struct timespec * ts, void * uts)
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
