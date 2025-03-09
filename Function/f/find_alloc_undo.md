# Function: <code>find_alloc_undo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582155624,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1688",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SYSC_semtimedop"
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
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582371840,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1686",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SYSC_semtimedop"
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
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582463722,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1677",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SYSC_semtimedop"
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
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582543098,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1690",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SYSC_semtimedop"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582692765,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1783",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582890971,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1858",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582999124,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1865",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583178816,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1887",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583178816,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284736,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284736,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614256,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1904",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614256,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734624,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1903",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734624,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1034
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583759936,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1905",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583759936,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1031
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1908",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123184,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
    },
    {
      "addr": 18446744071592291166,
      "name": "find_alloc_undo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1906",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716064,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
    },
    {
      "addr": 18446744071594073194,
      "name": "find_alloc_undo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1906",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585408928,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
    },
    {
      "addr": 18446744071596092899,
      "name": "find_alloc_undo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1906",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639728,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
    },
    {
      "addr": 18446744071596616247,
      "name": "find_alloc_undo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1906",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585886416,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1062
    },
    {
      "addr": 18446744071597522151,
      "name": "find_alloc_undo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495021160,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495021160,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228428872,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228428872,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288907584,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274303760,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274303760,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253472,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253472,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583190624,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190624,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237504,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237504,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```

```json
{
  "name": "find_alloc_undo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583329184,
      "name": "find_alloc_undo",
      "external": false,
      "loc": "ipc/sem.c:1888",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329184,
      "name": "find_alloc_undo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct sem_undo * find_alloc_undo(struct ipc_namespace * ns, int semid)
```
</details>
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
