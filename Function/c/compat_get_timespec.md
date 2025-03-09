# Function: <code>compat_get_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579959136,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:175",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex_compat.c:compat_SyS_futex",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait",
        "kernel/compat.c:compat_convert_timespec",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_SyS_clock_settime",
        "kernel/compat.c:compat_SyS_clock_nanosleep",
        "fs/compat.c:compat_SyS_utimensat",
        "fs/compat.c:compat_SyS_utimensat",
        "fs/compat.c:compat_SyS_io_getevents",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959136,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988720,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:175",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex_compat.c:compat_SyS_futex",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait",
        "kernel/compat.c:compat_SyS_clock_nanosleep",
        "kernel/compat.c:compat_SyS_clock_settime",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_convert_timespec",
        "fs/compat.c:compat_SyS_io_getevents",
        "fs/compat.c:compat_SyS_utimensat",
        "fs/compat.c:compat_SyS_utimensat",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988720,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019248,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:175",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex_compat.c:compat_SyS_futex",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait",
        "kernel/compat.c:compat_SyS_clock_nanosleep",
        "kernel/compat.c:compat_SyS_clock_settime",
        "kernel/compat.c:compat_SyS_nanosleep",
        "kernel/compat.c:compat_convert_timespec",
        "fs/aio.c:compat_SyS_io_getevents",
        "fs/compat.c:compat_SyS_utimensat",
        "fs/compat.c:compat_SyS_utimensat",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019248,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580026560,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:185",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_rt_sigtimedwait",
        "kernel/futex_compat.c:compat_SyS_futex",
        "kernel/compat.c:compat_convert_timespec",
        "fs/utimes.c:compat_SyS_utimensat",
        "fs/utimes.c:compat_SyS_utimensat",
        "fs/aio.c:compat_SyS_io_getevents",
        "ipc/mqueue.c:compat_SyS_mq_timedreceive",
        "ipc/mqueue.c:compat_SyS_mq_timedsend",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026560,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073456,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:185",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_rt_sigtimedwait",
        "kernel/futex_compat.c:compat_SyS_futex",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073456,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132784,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:142",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_compat_sys_rt_sigtimedwait",
        "kernel/futex_compat.c:__x32_compat_sys_futex",
        "kernel/futex_compat.c:__ia32_compat_sys_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132784,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580179984,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:142",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179984,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580225872,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:75",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225872,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580274112,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:75",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274112,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491515416,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:75",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491515416,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284484480,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:75",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284484480,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580242912,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:75",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242912,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580190464,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:75",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190464,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580234160,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:75",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234160,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int compat_get_timespec(struct timespec * ts, const void * uts)
```

```json
{
  "name": "compat_get_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580287152,
      "name": "compat_get_timespec",
      "external": true,
      "loc": "kernel/compat.c:75",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287152,
      "name": "compat_get_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int compat_get_timespec(struct timespec * ts, const void * uts)
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
int compat_get_timespec(struct timespec * ts, const void * uts)
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
int compat_get_timespec(struct timespec * ts, const void * uts)
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
