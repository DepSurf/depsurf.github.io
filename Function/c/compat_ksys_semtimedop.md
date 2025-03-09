# Function: <code>compat_ksys_semtimedop</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct compat_timespec * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582895920,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2208",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_semtimedop",
        "ipc/sem.c:__ia32_compat_sys_semtimedop",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895920,
      "name": "compat_ksys_semtimedop",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583004048,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2215",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_semtimedop",
        "ipc/sem.c:__ia32_compat_sys_semtimedop",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004048,
      "name": "compat_ksys_semtimedop",
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
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583185552,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2237",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185552,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583291344,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2238",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291344,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583618800,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2254",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621936,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583739552,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2253",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742576,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583766241,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2255",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766784,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584128433,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2279",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128688,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584725535,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2276",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726000,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585418895,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2277",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419216,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585649343,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2277",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649856,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585896079,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2275",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896592,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495027768,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2238",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__arm64_sys_semtimedop_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495027768,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228433172,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2238",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semtimedop_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228433172,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288912432,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2238",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semtimedop_time32",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288912432,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583260080,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2238",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260080,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583197232,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2238",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197232,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583244112,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2238",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244112,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
```

```json
{
  "name": "compat_ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583338528,
      "name": "compat_ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2238",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338528,
      "name": "compat_ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct compat_timespec * timeout)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct compat_timespec * timeout</code> ➡️ <code>const struct old_timespec32 * timeout</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int compat_ksys_semtimedop(int semid, struct sembuf * tsems, unsigned int nsops, const struct old_timespec32 * timeout)
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
