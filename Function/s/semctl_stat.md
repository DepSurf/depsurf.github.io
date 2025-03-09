# Function: <code>semctl_stat</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687584,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1183",
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
      "addr": 18446744071582687584,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582886688,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1220",
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
      "addr": 18446744071582886688,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994800,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1219",
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
      "addr": 18446744071582994800,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583175888,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
      "addr": 18446744071583175888,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281856,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
      "addr": 18446744071583281856,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583610944,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1231",
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
      "addr": 18446744071583610944,
      "name": "semctl_stat",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731296,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1230",
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
      "addr": 18446744071583731296,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583760976,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1232",
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
      "addr": 18446744071583760976,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1235",
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
      "addr": 18446744071584121616,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071592291145,
      "name": "semctl_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1234",
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
      "addr": 18446744071584708688,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071594073124,
      "name": "semctl_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1234",
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
      "addr": 18446744071585401344,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071596092829,
      "name": "semctl_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1234",
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
      "addr": 18446744071585632096,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071596616178,
      "name": "semctl_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1234",
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
      "addr": 18446744071585878864,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071597522082,
      "name": "semctl_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495017608,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
      "addr": 18446603336495017608,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228427412,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288900272,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
      "addr": 13835058055288900272,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274307680,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583250592,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
      "addr": 18446744071583250592,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583187744,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
      "addr": 18446744071583187744,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234624,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
      "addr": 18446744071583234624,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
```

```json
{
  "name": "semctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322992,
      "name": "semctl_stat",
      "external": false,
      "loc": "ipc/sem.c:1215",
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
      "addr": 18446744071583322992,
      "name": "semctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
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
int semctl_stat(struct ipc_namespace * ns, int semid, int cmd, struct semid64_ds * semid64)
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
