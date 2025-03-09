# Function: <code>compat_ksys_msgsnd</code>

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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582876854,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:917",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880160,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582986534,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:927",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988256,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583165577,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:952",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169584,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583271641,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275600,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583599848,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:976",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603616,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583720152,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:976",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723984,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583744610,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:978",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748368,
      "name": "compat_ksys_msgsnd",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584106450,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:978",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x64_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110080,
      "name": "compat_ksys_msgsnd",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584704002,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:978",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706592,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585395922,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:984",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398736,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585626626,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:984",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629424,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585873346,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:984",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876144,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495009960,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__arm64_compat_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495009960,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288890784,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_compat_sys_msgsnd",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288890784,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583240377,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244336,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583177529,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181488,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583224409,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228368,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
```

```json
{
  "name": "compat_ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583322377,
      "name": "compat_ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322640,
      "name": "compat_ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
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
long int compat_ksys_msgsnd(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, int msgflg)
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
