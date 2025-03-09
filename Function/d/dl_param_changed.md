# Function: <code>dl_param_changed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579540689,
      "name": "dl_param_changed",
      "external": false,
      "loc": "kernel/sched/core.c:3770",
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
  "name": "dl_param_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579552132,
      "name": "dl_param_changed",
      "external": false,
      "loc": "kernel/sched/core.c:4023",
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
  "name": "dl_param_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579576893,
      "name": "dl_param_changed",
      "external": false,
      "loc": "kernel/sched/core.c:4060",
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668736,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2584",
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
      "addr": 18446744071579668736,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699184,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2571",
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
      "addr": 18446744071579699184,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733280,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2661",
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
      "addr": 18446744071579733280,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772960,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2664",
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
      "addr": 18446744071579772960,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800368,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2655",
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
      "addr": 18446744071579800368,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848208,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 18446744071579848208,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886880,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 18446744071579886880,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880800,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2851",
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
      "addr": 18446744071579880800,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889888,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2835",
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
      "addr": 18446744071579889888,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580004272,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2849",
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
      "addr": 18446744071580004272,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135264,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2991",
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
      "addr": 18446744071580135264,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309632,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2991",
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
      "addr": 18446744071580309632,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580377152,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:3017",
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
      "addr": 18446744071580377152,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580435152,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:3121",
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
      "addr": 18446744071580435152,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491038032,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 18446603336491038032,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225047840,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 3225047840,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283917040,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 13835058055283917040,
      "name": "dl_param_changed",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271639414,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 18446743936271639414,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820560,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 18446744071579820560,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755168,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 18446744071579755168,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808576,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 18446744071579808576,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "dl_param_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853632,
      "name": "dl_param_changed",
      "external": true,
      "loc": "kernel/sched/deadline.c:2702",
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
      "addr": 18446744071579853632,
      "name": "dl_param_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool dl_param_changed(struct task_struct * p, const struct sched_attr * attr)
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
