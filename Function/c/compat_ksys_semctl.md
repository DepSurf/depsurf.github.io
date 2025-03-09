# Function: <code>compat_ksys_semctl</code>

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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582895232,
      "name": "compat_ksys_semctl",
      "external": true,
      "loc": "ipc/sem.c:1740",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895232,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583003344,
      "name": "compat_ksys_semctl",
      "external": true,
      "loc": "ipc/sem.c:1747",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003344,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583183856,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1756",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583183856,
      "name": "compat_ksys_semctl",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289648,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1756",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289648,
      "name": "compat_ksys_semctl",
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620336,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1772",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620336,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740976,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1771",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740976,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761360,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1773",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761360,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122016,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1776",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x64_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x64_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122016,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584720112,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1774",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720112,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585413024,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1774",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413024,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585643744,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1774",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585643744,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585890480,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1774",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890480,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495026072,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1756",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__arm64_compat_sys_old_semctl",
        "ipc/sem.c:__arm64_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495026072,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288906112,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1756",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_compat_sys_old_semctl",
        "ipc/sem.c:__se_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288906112,
      "name": "compat_ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258384,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1756",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258384,
      "name": "compat_ksys_semctl",
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195536,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1756",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195536,
      "name": "compat_ksys_semctl",
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242416,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1756",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242416,
      "name": "compat_ksys_semctl",
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
```

```json
{
  "name": "compat_ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583336832,
      "name": "compat_ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1756",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__x32_compat_sys_old_semctl",
        "ipc/sem.c:__ia32_compat_sys_old_semctl",
        "ipc/sem.c:__x32_compat_sys_semctl",
        "ipc/sem.c:__ia32_compat_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583336832,
      "name": "compat_ksys_semctl",
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg)
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
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
long int compat_ksys_semctl(int semid, int semnum, int cmd, int arg, int version)
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
