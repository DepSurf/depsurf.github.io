# Function: <code>ksys_msgrcv</code>

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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582878901,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1189",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880224,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582985013,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1199",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988320,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583169237,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1224",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169648,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583275253,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275664,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583603269,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1256",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603696,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583723637,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1256",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724064,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583748021,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1258",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748432,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109733,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1258",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110144,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584706181,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1258",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706704,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585398245,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1264",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398864,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585628933,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1264",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629552,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585875653,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1264",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876272,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495005072,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__arm64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495010400,
      "name": "ksys_msgrcv",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228418956,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__se_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228418888,
      "name": "ksys_msgrcv",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288890192,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__se_sys_msgrcv"
      ],
      "caller_func": [
        "ipc/syscall.c:ksys_ipc",
        "ipc/syscall.c:ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288891024,
      "name": "ksys_msgrcv",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274296772,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__se_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274296660,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243989,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244400,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583181141,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181552,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583228021,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228432,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
```

```json
{
  "name": "ksys_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583320773,
      "name": "ksys_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:1225",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322704,
      "name": "ksys_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int ksys_msgrcv(int msqid, struct msgbuf * msgp, size_t msgsz, long int msgtyp, int msgflg)
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
