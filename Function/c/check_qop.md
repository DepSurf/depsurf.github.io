# Function: <code>check_qop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_qop(struct sem_array * sma, int semnum, struct sem_queue * q, bool count_zero)
```

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149760,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1016",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149760,
      "name": "check_qop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582368640,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1012",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368640,
      "name": "check_qop.constprop.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582460448,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1008",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460448,
      "name": "check_qop.constprop.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582539280,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1019",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539280,
      "name": "check_qop.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582689056,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1022",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689056,
      "name": "check_qop.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1058",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881232,
      "name": "check_qop.constprop.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071582897509,
      "name": "check_qop.constprop.24.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1057",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989344,
      "name": "check_qop.constprop.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071583005682,
      "name": "check_qop.constprop.24.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170672,
      "name": "check_qop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071583187158,
      "name": "check_qop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276656,
      "name": "check_qop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071583292972,
      "name": "check_qop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583604975,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1069",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:count_semcnt"
      ],
      "caller_func": [
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604736,
      "name": "check_qop.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071583623911,
      "name": "check_qop.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583725327,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1068",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:count_semcnt"
      ],
      "caller_func": [
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725088,
      "name": "check_qop.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071591361185,
      "name": "check_qop.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583749711,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1070",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:count_semcnt"
      ],
      "caller_func": [
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749472,
      "name": "check_qop.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071591304008,
      "name": "check_qop.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584111391,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1073",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:count_semcnt"
      ],
      "caller_func": [
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111136,
      "name": "check_qop.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071592290801,
      "name": "check_qop.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584708537,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1072",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:count_semcnt"
      ],
      "caller_func": [
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707872,
      "name": "check_qop.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071594072908,
      "name": "check_qop.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585401097,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1072",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:count_semcnt"
      ],
      "caller_func": [
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585400352,
      "name": "check_qop.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071596092746,
      "name": "check_qop.constprop.0.isra.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585631834,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1072",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:count_semcnt"
      ],
      "caller_func": [
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585631040,
      "name": "check_qop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071596616097,
      "name": "check_qop.isra.0.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585878602,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1072",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:count_semcnt"
      ],
      "caller_func": [
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585877808,
      "name": "check_qop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071597522001,
      "name": "check_qop.isra.0.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495011408,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495011408,
      "name": "check_qop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228419748,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228419748,
      "name": "check_qop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288893040,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288893040,
      "name": "check_qop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274299080,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274299080,
      "name": "check_qop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245392,
      "name": "check_qop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071583261708,
      "name": "check_qop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583182544,
      "name": "check_qop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071583198860,
      "name": "check_qop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229424,
      "name": "check_qop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071583245740,
      "name": "check_qop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "check_qop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_qop",
      "external": false,
      "loc": "ipc/sem.c:1053",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:count_semcnt",
        "ipc/sem.c:count_semcnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324496,
      "name": "check_qop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071583340152,
      "name": "check_qop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int check_qop(struct sem_array * sma, int semnum, struct sem_queue * q, bool count_zero)
```
</details>
</li>
</ul>
