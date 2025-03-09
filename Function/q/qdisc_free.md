# Function: <code>qdisc_free</code>

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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737488,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:717",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737488,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588074352,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:934",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588074352,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588252112,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:945",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588252112,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588643232,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:937",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588643232,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588865616,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588865616,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589743205,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:937",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_free_cb"
      ],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589749744,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589776306,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:924",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_free_cb"
      ],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589782720,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589680914,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:968",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_free_cb"
      ],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589686608,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590437522,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:994",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_free_cb"
      ],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590443904,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592041714,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:1036",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_free_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592045936,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593859250,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:1032",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_free_cb"
      ],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593864000,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594234114,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:1032",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_free_cb"
      ],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594238880,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595031458,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:1034",
      "file": "net/sched/sch_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_free_cb"
      ],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595036176,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502451944,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502451944,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235168712,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235168712,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296003840,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296003840,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278638928,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278638928,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588472000,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472000,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588184000,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184000,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588804176,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588804176,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void qdisc_free(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588944816,
      "name": "qdisc_free",
      "external": true,
      "loc": "net/sched/sch_generic.c:932",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_free_cb",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944816,
      "name": "qdisc_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void qdisc_free(struct Qdisc * qdisc)
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
