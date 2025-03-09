# Function: <code>preferred_group_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579609360,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:1743",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579623055,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:1856",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621856,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:1988",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621856,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1582
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601296,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:1984",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601296,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1588
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633648,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2036",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633648,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1588
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655680,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2064",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655680,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1547
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698128,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2013",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698128,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1547
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579730688,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2082",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730688,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773952,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2040",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773952,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812192,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2269",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812192,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1613
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802736,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2283",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802736,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1613
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809136,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2280",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809136,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1586
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579906288,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2269",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906288,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1586
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018624,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2274",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018624,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1637
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580187520,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2469",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580187520,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1598
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252704,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2469",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252704,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1606
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580302448,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2710",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302448,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1606
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
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490973440,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2040",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_placement"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283817536,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2040",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_placement"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579749808,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2040",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749808,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680192,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2040",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680192,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734320,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2040",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734320,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
int preferred_group_nid(struct task_struct * p, int nid)
```

```json
{
  "name": "preferred_group_nid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781984,
      "name": "preferred_group_nid",
      "external": false,
      "loc": "kernel/sched/fair.c:2040",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781984,
      "name": "preferred_group_nid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int preferred_group_nid(struct task_struct * p, int nid)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int preferred_group_nid(struct task_struct * p, int nid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int preferred_group_nid(struct task_struct * p, int nid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int preferred_group_nid(struct task_struct * p, int nid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int preferred_group_nid(struct task_struct * p, int nid)
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
