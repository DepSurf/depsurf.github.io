# Function: <code>ksys_semtimedop</code>

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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582895712,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2189",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895712,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583003840,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2196",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003840,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583185344,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2218",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185344,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583291136,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291136,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583618874,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2235",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621792,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583739626,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2234",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742432,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583766317,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2236",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766640,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584128509,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2260",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128544,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584725635,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2257",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584725840,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585418995,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2258",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419040,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585649443,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2258",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649680,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585896179,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2256",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896416,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495027528,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__arm64_sys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495027528,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228432988,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228432988,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288912160,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semtimedop",
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:ksys_ipc",
        "ipc/syscall.c:ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288912160,
      "name": "ksys_semtimedop",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274308998,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274308998,
      "name": "ksys_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583259872,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259872,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583197024,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197024,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243904,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243904,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct __kernel_timespec * timeout)
```

```json
{
  "name": "ksys_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583338320,
      "name": "ksys_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2219",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338320,
      "name": "ksys_semtimedop",
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
long int ksys_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec * timeout</code> ➡️ <code>const struct __kernel_timespec * timeout</code>
</li>
</ul>
</details>
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
