# Function: <code>__accumulate_pelt_segments</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589552,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/fair.c:2824",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589552,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618960,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/fair.c:3071",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618960,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650448,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/fair.c:3097",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650448,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791056,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:62",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791056,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818848,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818848,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866944,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866944,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579912172,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se"
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
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579905638,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:61",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se"
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
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579914658,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:61",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se"
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
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580036084,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:61",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se"
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
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580125365,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:57",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se"
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
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580299077,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:57",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se"
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
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580366500,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:57",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se"
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
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580422100,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:57",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se"
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491065624,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491065624,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225067464,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225067464,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283944848,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283944848,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271656432,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271656432,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579839296,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839296,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774032,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774032,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827312,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827312,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
```

```json
{
  "name": "__accumulate_pelt_segments",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872464,
      "name": "__accumulate_pelt_segments",
      "external": false,
      "loc": "kernel/sched/pelt.c:63",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872464,
      "name": "__accumulate_pelt_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
u32 __accumulate_pelt_segments(u64 periods, u32 d1, u32 d3)
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
