# Function: <code>compat_ksys_old_semctl</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583184474,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1807",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185312,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583290266,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1807",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291104,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583620970,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1823",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621760,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583741610,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1822",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742400,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583761994,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1824",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766608,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584122650,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1827",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x64_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124512,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584720650,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1825",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721504,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585413594,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1825",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585414560,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585644330,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1825",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645280,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585891066,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1825",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585892016,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495026656,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1807",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__arm64_compat_sys_old_semctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495027448,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288906816,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1807",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__se_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288912112,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583259002,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1807",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259840,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583196154,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1807",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196992,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243034,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1807",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243872,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_old_semctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583337450,
      "name": "compat_ksys_old_semctl",
      "external": true,
      "loc": "ipc/sem.c:1807",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338288,
      "name": "compat_ksys_old_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
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
long int compat_ksys_old_semctl(int semid, int semnum, int cmd, int arg)
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
