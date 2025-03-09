# Function: <code>__update_load_avg_blocked_se</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590704,
      "name": "__update_load_avg_blocked_se",
      "external": false,
      "loc": "kernel/sched/fair.c:2994",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590704,
      "name": "__update_load_avg_blocked_se.isra.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579619696,
      "name": "__update_load_avg_blocked_se",
      "external": false,
      "loc": "kernel/sched/fair.c:3280",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619696,
      "name": "__update_load_avg_blocked_se.isra.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579651504,
      "name": "__update_load_avg_blocked_se",
      "external": false,
      "loc": "kernel/sched/fair.c:3330",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579651504,
      "name": "__update_load_avg_blocked_se.isra.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
int __update_load_avg_blocked_se(u64 now, int cpu, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791200,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:270",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791200,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818992,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818992,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867088,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867088,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908176,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:303",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908176,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901824,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:299",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901824,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910896,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:299",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910896,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029968,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:299",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029968,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117120,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:295",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117120,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580290800,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:295",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290800,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580358208,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:295",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580358208,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580413776,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:295",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413776,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491065824,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491065824,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225067708,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sync_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225067708,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283945040,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283945040,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271656610,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271656610,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579839440,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839440,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774176,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774176,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827456,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827456,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int __update_load_avg_blocked_se(u64 now, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_blocked_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872608,
      "name": "__update_load_avg_blocked_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:266",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872608,
      "name": "__update_load_avg_blocked_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __update_load_avg_blocked_se(u64 now, int cpu, struct sched_entity * se)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>now, cpu, se</code> ➡️ <code>now, se</code>
</li>
</ul>
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
