# Function: <code>update_stats_enqueue_sleeper</code>

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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579639617,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:933",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579618006,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:930",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579649755,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:910",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579681145,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:897",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579715801,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:893",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579749649,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:925",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579791681,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void update_stats_enqueue_sleeper(struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835504,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:935",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835504,
      "name": "update_stats_enqueue_sleeper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
void update_stats_enqueue_sleeper(struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827680,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:942",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827680,
      "name": "update_stats_enqueue_sleeper",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void update_stats_enqueue_sleeper(struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821360,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:939",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821360,
      "name": "update_stats_enqueue_sleeper",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void update_stats_enqueue_sleeper(struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:925",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925344,
      "name": "update_stats_enqueue_sleeper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
    },
    {
      "addr": 18446744071592109170,
      "name": "update_stats_enqueue_sleeper.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490971276,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224982816,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283836644,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271591930,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579767537,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579698129,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579752049,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:enqueue_entity"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void update_stats_enqueue_sleeper(struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "update_stats_enqueue_sleeper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789712,
      "name": "update_stats_enqueue_sleeper",
      "external": false,
      "loc": "kernel/sched/fair.c:924",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789712,
      "name": "update_stats_enqueue_sleeper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void update_stats_enqueue_sleeper(struct cfs_rq * cfs_rq, struct sched_entity * se)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void update_stats_enqueue_sleeper(struct cfs_rq * cfs_rq, struct sched_entity * se)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➕</summary>

```c
void update_stats_enqueue_sleeper(struct cfs_rq * cfs_rq, struct sched_entity * se)
```
</details>
</li>
</ul>
