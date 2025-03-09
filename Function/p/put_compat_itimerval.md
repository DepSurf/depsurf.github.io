# Function: <code>put_compat_itimerval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579960827,
      "name": "put_compat_itimerval",
      "external": false,
      "loc": "kernel/compat.c:300",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_getitimer",
        "kernel/compat.c:compat_SyS_setitimer"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579991706,
      "name": "put_compat_itimerval",
      "external": false,
      "loc": "kernel/compat.c:300",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_setitimer",
        "kernel/compat.c:compat_SyS_getitimer"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580022202,
      "name": "put_compat_itimerval",
      "external": false,
      "loc": "kernel/compat.c:300",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_setitimer",
        "kernel/compat.c:compat_SyS_getitimer"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027712,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:239",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:compat_SyS_setitimer",
        "kernel/time/itimer.c:compat_SyS_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027712,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580074528,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:216",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:compat_SyS_setitimer",
        "kernel/time/itimer.c:compat_SyS_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074528,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134112,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:173",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134112,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181328,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:173",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181328,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226736,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:106",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226736,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274944,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:106",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274944,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491518568,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:106",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__arm64_compat_sys_setitimer",
        "kernel/time/itimer.c:__arm64_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491518568,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284485472,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:106",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__se_compat_sys_setitimer",
        "kernel/time/itimer.c:__se_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284485472,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243744,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:106",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243744,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191296,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:106",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191296,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580234992,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:106",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234992,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
```

```json
{
  "name": "put_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287984,
      "name": "put_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:106",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer",
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287984,
      "name": "put_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
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
int put_compat_itimerval(struct compat_itimerval * o, const struct itimerval * i)
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
