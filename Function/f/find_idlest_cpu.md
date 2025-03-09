# Function: <code>find_idlest_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579579434,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:4805",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579590824,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5222",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579650850,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5533",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579597244,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5515",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579627153,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5963",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579660658,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6188",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579695198,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5928",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725248,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5793",
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
      "addr": 18446744071579725248,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1640
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579767712,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 18446744071579767712,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809392,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5920",
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
      "addr": 18446744071579809392,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800720,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5969",
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
      "addr": 18446744071579800720,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807920,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6032",
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
      "addr": 18446744071579807920,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
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
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579913756,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6082",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580033844,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6139",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213492,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6514",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580270697,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6767",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580318068,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:7163",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490948944,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 18446603336490948944,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1560
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224962944,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 3224962944,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1628
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283801760,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 13835058055283801760,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1952
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271575016,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 18446743936271575016,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1338
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743568,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 18446744071579743568,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673952,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 18446744071579673952,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579728080,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 18446744071579728080,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
```

```json
{
  "name": "find_idlest_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775856,
      "name": "find_idlest_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:5748",
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
      "addr": 18446744071579775856,
      "name": "find_idlest_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
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
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int find_idlest_cpu(struct sched_domain * sd, struct task_struct * p, int cpu, int prev_cpu, int sd_flag)
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
