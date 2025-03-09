# Function: <code>ksys_semctl</code>

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
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582894832,
      "name": "ksys_semctl",
      "external": true,
      "loc": "ipc/sem.c:1630",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582894832,
      "name": "ksys_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002896,
      "name": "ksys_semctl",
      "external": true,
      "loc": "ipc/sem.c:1637",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002896,
      "name": "ksys_semctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583184512,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184512,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583290304,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290304,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583621008,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1649",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621008,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583741648,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1648",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741648,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583762032,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1650",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583762032,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584122688,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1653",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122688,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584720704,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1651",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720704,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585413664,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1651",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413664,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585644400,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1651",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585644400,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585891136,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1651",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891136,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495026736,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__arm64_sys_semctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg, int version)
```

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228427156,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:ksys_old_semctl",
        "ipc/sem.c:__se_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228427156,
      "name": "ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1716
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
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg, int version)
```

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288905456,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:ksys_old_semctl",
        "ipc/sem.c:__se_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288905456,
      "name": "ksys_semctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274307578,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__se_sys_semctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583259040,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259040,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583196192,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196192,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243072,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243072,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_semctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583337488,
      "name": "ksys_semctl",
      "external": false,
      "loc": "ipc/sem.c:1633",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semctl",
        "ipc/sem.c:__x64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337488,
      "name": "ksys_semctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg, int version)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long int ksys_semctl(int semid, int semnum, int cmd, long unsigned int arg, int version)
```
</details>
</li>
</ul>
