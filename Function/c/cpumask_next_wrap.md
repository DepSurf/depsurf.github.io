# Function: <code>cpumask_next_wrap</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579620841,
      "name": "cpumask_next_wrap",
      "external": false,
      "loc": "kernel/sched/fair.c:5593",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199424,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:58",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199424,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588748256,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:75",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748256,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126000,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:76",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126000,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589360688,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:76",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360688,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817744,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817744,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590044064,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044064,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585037920,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585037920,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189824,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189824,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072976,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072976,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585519664,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519664,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672192,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672192,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
unsigned int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595751680,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:22",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595751680,
      "name": "cpumask_next_wrap",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596276064,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:22",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_find_next",
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596276064,
      "name": "cpumask_next_wrap",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597160752,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:22",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_find_next",
        "drivers/net/virtio_net.c:virtnet_set_affinity",
        "lib/objpool.c:objpool_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597160752,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503805192,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503805192,
      "name": "cpumask_next_wrap",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236428328,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236428328,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297644304,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297644304,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279702072,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279702072,
      "name": "cpumask_next_wrap",
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646320,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646320,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372192,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next",
        "drivers/scsi/storvsc_drv.c:storvsc_queuecommand",
        "drivers/scsi/storvsc_drv.c:storvsc_queuecommand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372192,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590089696,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590089696,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
```

```json
{
  "name": "cpumask_next_wrap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590139952,
      "name": "cpumask_next_wrap",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/padata.c:padata_find_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590139952,
      "name": "cpumask_next_wrap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cpumask_next_wrap(int n, const struct cpumask * mask, int start, bool wrap)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
