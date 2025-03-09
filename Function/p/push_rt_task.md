# Function: <code>push_rt_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579634144,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1715",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_irq_work_func"
      ],
      "caller_func": [
        "kernel/sched/rt.c:push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634144,
      "name": "push_rt_task.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579649853,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1778",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_irq_work_func"
      ],
      "caller_func": [
        "kernel/sched/rt.c:push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649136,
      "name": "push_rt_task.part.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579674509,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1777",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_irq_work_func"
      ],
      "caller_func": [
        "kernel/sched/rt.c:push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673808,
      "name": "push_rt_task.part.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579648671,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1788",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_irq_work_func"
      ],
      "caller_func": [
        "kernel/sched/rt.c:push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647968,
      "name": "push_rt_task.part.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679200,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1778",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679200,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713888,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1789",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713888,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752048,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1802",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752048,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1802",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780672,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    },
    {
      "addr": 18446744071579783964,
      "name": "push_rt_task.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826176,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826176,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579865696,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1862",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:task_woken_rt",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865696,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858857,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1864",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_woken_rt",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ],
      "caller_func": [
        "kernel/sched/rt.c:task_woken_rt",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858000,
      "name": "push_rt_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
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
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579868345,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1864",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_woken_rt",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ],
      "caller_func": [
        "kernel/sched/rt.c:task_woken_rt",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867488,
      "name": "push_rt_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579970569,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1889",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_woken_rt",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ],
      "caller_func": [
        "kernel/sched/rt.c:task_woken_rt",
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969648,
      "name": "push_rt_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 799
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
int push_rt_task(struct rq * rq, bool pull)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091936,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:2054",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091936,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
int push_rt_task(struct rq * rq, bool pull)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580264208,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:2053",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264208,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
int push_rt_task(struct rq * rq, bool pull)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330272,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:2057",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330272,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
int push_rt_task(struct rq * rq, bool pull)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580385280,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:2002",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580385280,
      "name": "push_rt_task",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491010672,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491010672,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225009756,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225009756,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283876592,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283876592,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271618352,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271618352,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799792,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799792,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732928,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732928,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786544,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786544,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
int push_rt_task(struct rq * rq)
```

```json
{
  "name": "push_rt_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829568,
      "name": "push_rt_task",
      "external": false,
      "loc": "kernel/sched/rt.c:1792",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:rto_push_irq_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829568,
      "name": "push_rt_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
int push_rt_task(struct rq * rq)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int push_rt_task(struct rq * rq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int push_rt_task(struct rq * rq, bool pull)
```
</details>
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
