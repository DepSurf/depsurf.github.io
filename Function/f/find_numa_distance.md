# Function: <code>find_numa_distance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561424,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/core.c:6577",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561424,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571680,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/core.c:6543",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571680,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596976,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/core.c:6640",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596976,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579679488,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1260",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679488,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579714352,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1263",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714352,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746112,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1258",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746112,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786096,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1462",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786096,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579813824,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1487",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813824,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579861600,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1488",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861600,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579902916,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1473",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902576,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579897812,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1532",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897472,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579906624,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1563",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906624,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580024896,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1694",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024896,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580197296,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580197296,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388192,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388192,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580456784,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1725",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580456784,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580516432,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1751",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580516432,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491059248,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1488",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491059248,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283937440,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1488",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283937440,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579833952,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1488",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833952,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579768528,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1488",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768528,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579821968,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1488",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821968,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool find_numa_distance(int distance)
```

```json
{
  "name": "find_numa_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579867088,
      "name": "find_numa_distance",
      "external": true,
      "loc": "kernel/sched/topology.c:1488",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_init_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867088,
      "name": "find_numa_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
bool find_numa_distance(int distance)
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
bool find_numa_distance(int distance)
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
