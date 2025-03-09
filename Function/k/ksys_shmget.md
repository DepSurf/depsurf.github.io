# Function: <code>ksys_shmget</code>

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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582898355,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:706",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903680,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583006515,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011968,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583188000,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194096,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583293808,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299904,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583625294,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632000,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745822,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:725",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752640,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583770046,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:725",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583776752,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584131934,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:821",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138880,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584731892,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:815",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736752,
      "name": "ksys_shmget",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585425412,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:831",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585430672,
      "name": "ksys_shmget",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585656100,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:831",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661344,
      "name": "ksys_shmget",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585902868,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:827",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908112,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495031416,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__arm64_sys_shmget"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495038624,
      "name": "ksys_shmget",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228440832,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__se_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228440832,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288916716,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__se_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288924800,
      "name": "ksys_shmget",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274316230,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__se_sys_shmget"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274316114,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583262544,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268640,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583199696,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205776,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583246576,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252672,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
```

```json
{
  "name": "ksys_shmget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583340992,
      "name": "ksys_shmget",
      "external": true,
      "loc": "ipc/shm.c:726",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583347152,
      "name": "ksys_shmget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long int ksys_shmget(key_t key, size_t size, int shmflg)
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
