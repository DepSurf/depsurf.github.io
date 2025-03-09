# Function: <code>__checkparam_dl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579540047,
      "name": "__checkparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:3724",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
  "name": "__checkparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551215,
      "name": "__checkparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:3977",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
  "name": "__checkparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579576077,
      "name": "__checkparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:4014",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668560,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2535",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668560,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699008,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2522",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699008,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733104,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2607",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733104,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772784,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2610",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772784,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800192,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2601",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800192,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848032,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848032,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886704,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2647",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886704,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880560,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2782",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880560,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889648,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2766",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889648,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580004032,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2780",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004032,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134992,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2922",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134992,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309328,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2922",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309328,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376848,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2948",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376848,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434800,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:3045",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434800,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491037840,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491037840,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225047588,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225047588,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283916848,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283916848,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271639260,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271639260,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820384,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820384,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579754992,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754992,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808400,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808400,
      "name": "__checkparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool __checkparam_dl(const struct sched_attr * attr)
```

```json
{
  "name": "__checkparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853456,
      "name": "__checkparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2648",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853456,
      "name": "__checkparam_dl",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool __checkparam_dl(const struct sched_attr * attr)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
