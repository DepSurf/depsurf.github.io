# Function: <code>compat_ksys_old_msgctl</code>

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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583167162,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:752",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169488,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583273178,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:753",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275504,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583601050,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:772",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603520,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721402,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:772",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723888,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745834,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:774",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748272,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584107530,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:774",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x64_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109984,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584701818,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:774",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706432,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585393594,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:780",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398544,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585624282,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:780",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629232,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585871002,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:780",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585875952,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495008448,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:753",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__arm64_compat_sys_old_msgctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495009440,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288888272,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:753",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__se_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288890528,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241914,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:753",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244240,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583179066,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:753",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181392,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583225946,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:753",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228272,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_old_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583318666,
      "name": "compat_ksys_old_msgctl",
      "external": true,
      "loc": "ipc/msg.c:753",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322544,
      "name": "compat_ksys_old_msgctl",
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
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
long int compat_ksys_old_msgctl(int msqid, int cmd, void * uptr)
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
