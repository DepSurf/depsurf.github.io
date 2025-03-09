# Function: <code>ksys_msgsnd</code>

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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582876712,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:894",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880096,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582986392,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:904",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988192,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583165432,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:929",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169520,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583271496,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275536,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583600008,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603552,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583720376,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:953",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723920,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583744839,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:955",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748304,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584106535,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:955",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110016,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584704231,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:955",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706480,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585396183,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:961",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398608,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585626887,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:961",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629296,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585873607,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:961",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876016,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495009512,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__arm64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495009512,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228418720,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228418720,
      "name": "ksys_msgsnd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288890576,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_sys_msgsnd",
        "ipc/syscall.c:ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288890576,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274296470,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274296470,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583240232,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244272,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583177384,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181424,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583224264,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228304,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
```

```json
{
  "name": "ksys_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583322232,
      "name": "ksys_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:930",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322576,
      "name": "ksys_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long int ksys_msgsnd(int msqid, struct msgbuf * msgp, size_t msgsz, int msgflg)
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
