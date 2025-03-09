# Function: <code>visit_groups_merge</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758352,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3246",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758352,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824816,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3241",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824816,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919488,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3265",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919488,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580972944,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972944,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581177472,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3562",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177472,
      "name": "visit_groups_merge.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581222688,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3630",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222688,
      "name": "visit_groups_merge.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581229312,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3652",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229312,
      "name": "visit_groups_merge.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1094
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
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3715",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487776,
      "name": "visit_groups_merge.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
    },
    {
      "addr": 18446744071592188233,
      "name": "visit_groups_merge.constprop.0.isra.0.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3626",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833248,
      "name": "visit_groups_merge.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
    },
    {
      "addr": 18446744071593963297,
      "name": "visit_groups_merge.constprop.0.isra.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3690",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260208,
      "name": "visit_groups_merge.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1333
    },
    {
      "addr": 18446744071596023331,
      "name": "visit_groups_merge.constprop.0.isra.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3690",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460896,
      "name": "visit_groups_merge.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1285
    },
    {
      "addr": 18446744071596545459,
      "name": "visit_groups_merge.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3734",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:ctx_groups_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629728,
      "name": "visit_groups_merge.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1285
    },
    {
      "addr": 18446744071597449238,
      "name": "visit_groups_merge.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492323096,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492323096,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226223896,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226223896,
      "name": "visit_groups_merge.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285579984,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285579984,
      "name": "visit_groups_merge.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272458398,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272458398,
      "name": "visit_groups_merge.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941744,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941744,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887808,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887808,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932992,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932992,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```

```json
{
  "name": "visit_groups_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994528,
      "name": "visit_groups_merge",
      "external": false,
      "loc": "kernel/events/core.c:3350",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994528,
      "name": "visit_groups_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```
</details>
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
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int visit_groups_merge(struct perf_event_groups * groups, int cpu, int (*)(struct perf_event *, void *) func, void * data)
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
