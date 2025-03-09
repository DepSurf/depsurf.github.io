# Function: <code>get_compat_itimerval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579961006,
      "name": "get_compat_itimerval",
      "external": false,
      "loc": "kernel/compat.c:290",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "get_compat_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579991534,
      "name": "get_compat_itimerval",
      "external": false,
      "loc": "kernel/compat.c:290",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580022030,
      "name": "get_compat_itimerval",
      "external": false,
      "loc": "kernel/compat.c:290",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027584,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:226",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:compat_SyS_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027584,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580074400,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:203",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:compat_SyS_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074400,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133984,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:160",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133984,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181200,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:160",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181200,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226608,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:93",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226608,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274816,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:93",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274816,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491518128,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:93",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__arm64_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491518128,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284485312,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:93",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__se_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284485312,
      "name": "get_compat_itimerval",
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243616,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:93",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243616,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191168,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:93",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191168,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580234864,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:93",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234864,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
```

```json
{
  "name": "get_compat_itimerval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287856,
      "name": "get_compat_itimerval",
      "external": true,
      "loc": "kernel/compat.c:93",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287856,
      "name": "get_compat_itimerval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
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
int get_compat_itimerval(struct itimerval * o, const struct compat_itimerval * i)
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
