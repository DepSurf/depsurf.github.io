# Function: <code>compat_ksys_old_shmctl</code>

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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195130,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195168,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583300938,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300976,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583630266,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632112,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583750874,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1395",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752752,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583775018,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1395",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583776864,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584137114,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1491",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x64_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138992,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584735370,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1485",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736880,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585429146,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1501",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585430816,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585659850,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1501",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661488,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585906618,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1497",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908256,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495039688,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__arm64_compat_sys_old_shmctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495039720,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288926000,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__se_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288926032,
      "name": "compat_ksys_old_shmctl",
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583269674,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269712,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583206810,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583206848,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583253706,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253744,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583348186,
      "name": "compat_ksys_old_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1397",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348224,
      "name": "compat_ksys_old_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
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
long int compat_ksys_old_shmctl(int shmid, int cmd, void * uptr)
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
