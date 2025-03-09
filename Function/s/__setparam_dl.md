# Function: <code>__setparam_dl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579519964,
      "name": "__setparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:3616",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__setscheduler_params"
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
  "name": "__setparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551338,
      "name": "__setparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:3869",
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
  "name": "__setparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579576200,
      "name": "__setparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:3906",
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668384,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2502",
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
      "addr": 18446744071579668384,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698832,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2489",
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
      "addr": 18446744071579698832,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732928,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2574",
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
      "addr": 18446744071579732928,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772608,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2577",
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
      "addr": 18446744071579772608,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800016,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2568",
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
      "addr": 18446744071579800016,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579847856,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 18446744071579847856,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886528,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2614",
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
      "addr": 18446744071579886528,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880384,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2741",
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
      "addr": 18446744071579880384,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889472,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2725",
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
      "addr": 18446744071579889472,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580003824,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2738",
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
      "addr": 18446744071580003824,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134768,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2888",
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
      "addr": 18446744071580134768,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309072,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2888",
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
      "addr": 18446744071580309072,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376592,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2914",
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
      "addr": 18446744071580376592,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434544,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:3011",
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
      "addr": 18446744071580434544,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491037656,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 18446603336491037656,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225047384,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 3225047384,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283916640,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 13835058055283916640,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271639084,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 18446743936271639084,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820208,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 18446744071579820208,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579754816,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 18446744071579754816,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808224,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 18446744071579808224,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "__setparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853280,
      "name": "__setparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2615",
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
      "addr": 18446744071579853280,
      "name": "__setparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __setparam_dl(struct task_struct * p, const struct sched_attr * attr)
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
