# Function: <code>sched_domains_numa_masks_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579527281,
      "name": "sched_domains_numa_masks_set",
      "external": false,
      "loc": "kernel/sched/core.c:6785",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_domains_numa_masks_update"
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
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579576513,
      "name": "sched_domains_numa_masks_set",
      "external": false,
      "loc": "kernel/sched/core.c:6751",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579602612,
      "name": "sched_domains_numa_masks_set",
      "external": false,
      "loc": "kernel/sched/core.c:6848",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681040,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1468",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681040,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716048,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1483",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716048,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747760,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1478",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747760,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787792,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1679",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787792,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815520,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1704",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815520,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863296,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1705",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863296,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579903920,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1690",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903920,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898832,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1749",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898832,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907936,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1777",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907936,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026432,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1965",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026432,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199408,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:2009",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199408,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580390256,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:2009",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390256,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580458848,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:2016",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580458848,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518496,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:2042",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518496,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491060952,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1705",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491060952,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_domains_numa_masks_set",
      "external": false,
      "loc": "kernel/sched/sched.h:1278",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283939648,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1705",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283939648,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_domains_numa_masks_set",
      "external": false,
      "loc": "kernel/sched/sched.h:1278",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835648,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1705",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835648,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770224,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1705",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770224,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823664,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1705",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823664,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868784,
      "name": "sched_domains_numa_masks_set",
      "external": true,
      "loc": "kernel/sched/topology.c:1705",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868784,
      "name": "sched_domains_numa_masks_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void sched_domains_numa_masks_set(unsigned int cpu)
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
void sched_domains_numa_masks_set(unsigned int cpu)
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
void sched_domains_numa_masks_set(unsigned int cpu)
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
