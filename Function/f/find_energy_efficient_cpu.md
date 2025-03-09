# Function: <code>find_energy_efficient_cpu</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579694325,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6496",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6390",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806064,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6546",
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
      "addr": 18446744071579806064,
      "name": "find_energy_efficient_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579796768,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6616",
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
      "addr": 18446744071579796768,
      "name": "find_energy_efficient_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802320,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6722",
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
      "addr": 18446744071579802320,
      "name": "find_energy_efficient_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898752,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6798",
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
      "addr": 18446744071579898752,
      "name": "find_energy_efficient_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
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
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011200,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6767",
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
      "addr": 18446744071580011200,
      "name": "find_energy_efficient_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179888,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:7196",
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
      "addr": 18446744071580179888,
      "name": "find_energy_efficient_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2363
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
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244576,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:7524",
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
      "addr": 18446744071580244576,
      "name": "find_energy_efficient_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2143
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
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580290896,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:7940",
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
      "addr": 18446744071580290896,
      "name": "find_energy_efficient_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1910
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
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_energy_efficient_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_energy_efficient_cpu",
      "external": false,
      "loc": "kernel/sched/fair.c:6336",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int find_energy_efficient_cpu(struct task_struct * p, int prev_cpu)
```
</details>
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
