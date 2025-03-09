# Function: <code>rto_next_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579628065,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1814",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:find_next_push_cpu"
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
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579642656,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1877",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:find_next_push_cpu"
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
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579667335,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1876",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:find_next_push_cpu"
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
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579643078,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1887",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:find_next_push_cpu"
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673312,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1910",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673312,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706048,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1921",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706048,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579745328,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1932",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745328,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773936,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1932",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773936,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816816,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816816,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579867469,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1992",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:tell_cpu_to_push"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579860236,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:2020",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:tell_cpu_to_push"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579868796,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:2020",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579978812,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:2045",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580105528,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:2222",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:rto_push_irq_work_func"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580278778,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:2221",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:rto_push_irq_work_func"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580346074,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:2225",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:rto_push_irq_work_func"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580400810,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:2172",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:rto_push_irq_work_func"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490999616,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490999616,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225006896,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225006896,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283870336,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283870336,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271608796,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271608796,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792416,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792416,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579723376,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723376,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777184,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777184,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int rto_next_cpu(struct root_domain * rd)
```

```json
{
  "name": "rto_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579825120,
      "name": "rto_next_cpu",
      "external": false,
      "loc": "kernel/sched/rt.c:1922",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825120,
      "name": "rto_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int rto_next_cpu(struct root_domain * rd)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int rto_next_cpu(struct root_domain * rd)
```
</details>
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
