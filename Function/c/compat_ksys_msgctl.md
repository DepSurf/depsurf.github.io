# Function: <code>compat_ksys_msgctl</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879552,
      "name": "compat_ksys_msgctl",
      "external": true,
      "loc": "ipc/msg.c:682",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879552,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987648,
      "name": "compat_ksys_msgctl",
      "external": true,
      "loc": "ipc/msg.c:692",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987648,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166528,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:704",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166528,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272576,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:705",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272576,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583600448,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:724",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600448,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720800,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:724",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720800,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583745264,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:726",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745264,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106960,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:726",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x64_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x64_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106960,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584701248,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:726",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701248,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392992,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:732",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392992,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623632,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:732",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623632,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585870352,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:732",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870352,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495007296,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:705",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__arm64_compat_sys_old_msgctl",
        "ipc/msg.c:__arm64_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495007296,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288887312,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:705",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_compat_sys_old_msgctl",
        "ipc/msg.c:__se_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288887312,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583241312,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:705",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241312,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583178464,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:705",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583178464,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583225344,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:705",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225344,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583318064,
      "name": "compat_ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:705",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_old_msgctl",
        "ipc/msg.c:__ia32_compat_sys_old_msgctl",
        "ipc/msg.c:__x32_compat_sys_msgctl",
        "ipc/msg.c:__ia32_compat_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583318064,
      "name": "compat_ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr)
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
<b>Param added. </b>
<code>int version</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
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
long int compat_ksys_msgctl(int msqid, int cmd, void * uptr, int version)
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
