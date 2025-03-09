# Function: <code>sync_entity_load_avg</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sync_entity_load_avg(struct sched_entity * se)
```

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650080,
      "name": "sync_entity_load_avg",
      "external": true,
      "loc": "kernel/sched/fair.c:3385",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650080,
      "name": "sync_entity_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void sync_entity_load_avg(struct sched_entity * se)
```

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579597862,
      "name": "sync_entity_load_avg",
      "external": true,
      "loc": "kernel/sched/fair.c:3490",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627280,
      "name": "sync_entity_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sync_entity_load_avg(struct sched_entity * se)
```

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579627711,
      "name": "sync_entity_load_avg",
      "external": true,
      "loc": "kernel/sched/fair.c:3826",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657968,
      "name": "sync_entity_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void sync_entity_load_avg(struct sched_entity * se)
```

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662402,
      "name": "sync_entity_load_avg",
      "external": true,
      "loc": "kernel/sched/fair.c:3884",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690432,
      "name": "sync_entity_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void sync_entity_load_avg(struct sched_entity * se)
```

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579697022,
      "name": "sync_entity_load_avg",
      "external": true,
      "loc": "kernel/sched/fair.c:3558",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728576,
      "name": "sync_entity_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579729660,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3648",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579772536,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579806215,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3836",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579796919,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3853",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579802471,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3901",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579914026,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3913",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580034066,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3962",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213714,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:4231",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580270911,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:4288",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580318290,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:4775",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490956316,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void sync_entity_load_avg(struct sched_entity * se)
```

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224962728,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
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
      "addr": 3224962728,
      "name": "sync_entity_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283808848,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271578790,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579748392,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579678776,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579732904,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_entity_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579780789,
      "name": "sync_entity_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3649",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:remove_entity_load_avg"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void sync_entity_load_avg(struct sched_entity * se)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void sync_entity_load_avg(struct sched_entity * se)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void sync_entity_load_avg(struct sched_entity * se)
```
</details>
</li>
</ul>
