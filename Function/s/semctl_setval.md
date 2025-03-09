# Function: <code>semctl_setval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582160697,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1267",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semctl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582376905,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1263",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semctl"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582468953,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1258",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semctl"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582549481,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1269",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semctl"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582696528,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1263",
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
      "addr": 18446744071582696528,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 838
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582889552,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1321",
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
      "addr": 18446744071582889552,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582997696,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1328",
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
      "addr": 18446744071582997696,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583182912,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
      "addr": 18446744071583182912,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583288704,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
      "addr": 18446744071583288704,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619040,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1340",
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
      "addr": 18446744071583619040,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1291
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739648,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1339",
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
      "addr": 18446744071583739648,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1313
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583758624,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1341",
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
      "addr": 18446744071583758624,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1344",
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
      "addr": 18446744071584120288,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1326
    },
    {
      "addr": 18446744071592291124,
      "name": "semctl_setval.cold",
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1343",
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
      "addr": 18446744071584712640,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1306
    },
    {
      "addr": 18446744071594073173,
      "name": "semctl_setval.cold",
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1343",
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
      "addr": 18446744071585405456,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1306
    },
    {
      "addr": 18446744071596092878,
      "name": "semctl_setval.cold",
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1343",
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
      "addr": 18446744071585636224,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1290
    },
    {
      "addr": 18446744071596616227,
      "name": "semctl_setval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1343",
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
      "addr": 18446744071585882912,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1287
    },
    {
      "addr": 18446744071597522131,
      "name": "semctl_setval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495025208,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
      "addr": 18446603336495025208,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228427548,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288904208,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
      "addr": 13835058055288904208,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
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
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274308310,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583257440,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
      "addr": 18446744071583257440,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194592,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
      "addr": 18446744071583194592,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583241472,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
      "addr": 18446744071583241472,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
```

```json
{
  "name": "semctl_setval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583335856,
      "name": "semctl_setval",
      "external": false,
      "loc": "ipc/sem.c:1324",
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
      "addr": 18446744071583335856,
      "name": "semctl_setval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
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
int semctl_setval(struct ipc_namespace * ns, int semid, int semnum, int val)
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
