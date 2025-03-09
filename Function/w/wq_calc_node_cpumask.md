# Function: <code>wq_calc_node_cpumask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465184,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3437",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465184,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479248,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3538",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479248,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505232,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3566",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505232,
      "name": "wq_calc_node_cpumask.isra.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579496912,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3564",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496912,
      "name": "wq_calc_node_cpumask.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579523264,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3575",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523264,
      "name": "wq_calc_node_cpumask.isra.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3648",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547504,
      "name": "wq_calc_node_cpumask.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579566630,
      "name": "wq_calc_node_cpumask.isra.26.cold.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3671",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585072,
      "name": "wq_calc_node_cpumask.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071579603862,
      "name": "wq_calc_node_cpumask.isra.28.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3812",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609120,
      "name": "wq_calc_node_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071579627413,
      "name": "wq_calc_node_cpumask.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634800,
      "name": "wq_calc_node_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071579653282,
      "name": "wq_calc_node_cpumask.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3830",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665328,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071579684995,
      "name": "wq_calc_node_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3843",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645200,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071591280344,
      "name": "wq_calc_node_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3850",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648640,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071591223226,
      "name": "wq_calc_node_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3889",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725360,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071592104094,
      "name": "wq_calc_node_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3872",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842240,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071593872179,
      "name": "wq_calc_node_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981824,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071595976271,
      "name": "wq_calc_node_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:4207",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034000,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071596493770,
      "name": "wq_calc_node_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490801112,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490801112,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224849336,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224849336,
      "name": "wq_calc_node_cpumask.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283636960,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283636960,
      "name": "wq_calc_node_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271477594,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271477594,
      "name": "wq_calc_node_cpumask.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611104,
      "name": "wq_calc_node_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071579629586,
      "name": "wq_calc_node_cpumask.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540176,
      "name": "wq_calc_node_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071579557938,
      "name": "wq_calc_node_cpumask.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608384,
      "name": "wq_calc_node_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071579626866,
      "name": "wq_calc_node_cpumask.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wq_calc_node_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "wq_calc_node_cpumask",
      "external": false,
      "loc": "kernel/workqueue.c:3821",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650352,
      "name": "wq_calc_node_cpumask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071579660581,
      "name": "wq_calc_node_cpumask.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
bool wq_calc_node_cpumask(const struct workqueue_attrs * attrs, int node, int cpu_going_down, cpumask_t * cpumask)
```
</details>
</li>
</ul>
