# Function: <code>select_idle_sibling</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579578880,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:4853",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578880,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590240,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5270",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590240,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579620608,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5789",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620608,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579595680,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5745",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595680,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579625680,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6191",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625680,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1027
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658784,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6423",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658784,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692944,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6164",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692944,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579727984,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6030",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727984,
      "name": "select_idle_sibling.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071579728960,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579770496,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770496,
      "name": "select_idle_sibling.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
    },
    {
      "addr": 18446744071579771840,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823280,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6191",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823280,
      "name": "select_idle_sibling",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814656,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6250",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814656,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811808,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6332",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811808,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1324
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
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911168,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6400",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911168,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2080
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
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031104,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6469",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031104,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2141
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
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580210096,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:6845",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210096,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2780
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
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267600,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:7119",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267600,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2463
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
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315216,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:7491",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315216,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2174
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490954104,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490954104,
      "name": "select_idle_sibling.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1404
    },
    {
      "addr": 18446603336490955512,
      "name": "select_idle_sibling",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224986028,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283806016,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283806016,
      "name": "select_idle_sibling.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1800
    },
    {
      "addr": 13835058055283807824,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271577720,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746352,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746352,
      "name": "select_idle_sibling.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
    },
    {
      "addr": 18446744071579747696,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579676736,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676736,
      "name": "select_idle_sibling.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
    },
    {
      "addr": 18446744071579678080,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579730864,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730864,
      "name": "select_idle_sibling.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
    },
    {
      "addr": 18446744071579732208,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
```

```json
{
  "name": "select_idle_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579778640,
      "name": "select_idle_sibling",
      "external": false,
      "loc": "kernel/sched/fair.c:5990",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_find_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778640,
      "name": "select_idle_sibling.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
    },
    {
      "addr": 18446744071579779984,
      "name": "select_idle_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int prev</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, target</code> ➡️ <code>p, prev, target</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int select_idle_sibling(struct task_struct * p, int prev, int target)
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
int select_idle_sibling(struct task_struct * p, int prev, int target)
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
