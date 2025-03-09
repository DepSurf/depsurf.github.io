# Function: <code>compat_ksys_msgrcv</code>

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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582878997,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1216",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880256,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582985109,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1226",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988352,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583169333,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1251",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169680,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583275349,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1252",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275696,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583603365,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1283",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603728,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583723733,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1283",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724096,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583748117,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1285",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748464,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109829,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1285",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x64_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110176,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584706245,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1285",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706752,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585398325,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1291",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398928,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585629013,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1291",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629616,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585875733,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1291",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876336,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495005136,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1252",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__arm64_compat_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495010504,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288890240,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1252",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__se_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288891056,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583244085,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1252",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244432,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583181237,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1252",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181584,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583228117,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1252",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228464,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
```

```json
{
  "name": "compat_ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583320869,
      "name": "compat_ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1252",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322736,
      "name": "compat_ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
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
long int compat_ksys_msgrcv(int msqid, compat_uptr_t msgp, compat_ssize_t msgsz, compat_long_t msgtyp, int msgflg)
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
