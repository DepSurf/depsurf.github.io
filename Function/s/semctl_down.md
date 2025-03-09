# Function: <code>semctl_down</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582154608,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1531",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154608,
      "name": "semctl_down.constprop.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582370816,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1529",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370816,
      "name": "semctl_down.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582462640,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1520",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582462640,
      "name": "semctl_down.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582541952,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1533",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541952,
      "name": "semctl_down.constprop.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582691728,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1519",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:C_SYSC_semctl",
        "ipc/sem.c:SYSC_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691728,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582886096,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1580",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582886096,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994208,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1587",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994208,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583175264,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175264,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281232,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281232,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583610320,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1599",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583610320,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730672,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1598",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730672,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755056,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1600",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755056,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584116672,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1603",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116672,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715456,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1601",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715456,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585408304,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1601",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585408304,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585639104,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1601",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639104,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585885792,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1601",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885792,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495018072,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:__arm64_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495018072,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228428088,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:ksys_semctl"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288899312,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288899312,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
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
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274308020,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249968,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249968,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583187120,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583187120,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234000,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234000,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328592,
      "name": "semctl_down",
      "external": false,
      "loc": "ipc/sem.c:1583",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328592,
      "name": "semctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
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
int semctl_down(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
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
