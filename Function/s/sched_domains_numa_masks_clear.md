# Function: <code>sched_domains_numa_masks_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579527189,
      "name": "sched_domains_numa_masks_clear",
      "external": false,
      "loc": "kernel/sched/core.c:6798",
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
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579576835,
      "name": "sched_domains_numa_masks_clear",
      "external": false,
      "loc": "kernel/sched/core.c:6764",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
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
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579602931,
      "name": "sched_domains_numa_masks_clear",
      "external": false,
      "loc": "kernel/sched/core.c:6861",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681248,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1481",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681248,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716256,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1496",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716256,
      "name": "sched_domains_numa_masks_clear",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747968,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1491",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747968,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788000,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1692",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788000,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815728,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1717",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815728,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863504,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863504,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904128,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1703",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904128,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899040,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1762",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899040,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908144,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1790",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908144,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026912,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1984",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026912,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199664,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:2026",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199664,
      "name": "sched_domains_numa_masks_clear",
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580390528,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:2026",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390528,
      "name": "sched_domains_numa_masks_clear",
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580459120,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:2033",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459120,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518768,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:2059",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518768,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491061240,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491061240,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_domains_numa_masks_clear",
      "external": false,
      "loc": "kernel/sched/sched.h:1279",
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283940016,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283940016,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_domains_numa_masks_clear",
      "external": false,
      "loc": "kernel/sched/sched.h:1279",
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835856,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835856,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770432,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770432,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823872,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823872,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
```

```json
{
  "name": "sched_domains_numa_masks_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868992,
      "name": "sched_domains_numa_masks_clear",
      "external": true,
      "loc": "kernel/sched/topology.c:1718",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868992,
      "name": "sched_domains_numa_masks_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sched_domains_numa_masks_clear(unsigned int cpu)
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
void sched_domains_numa_masks_clear(unsigned int cpu)
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
void sched_domains_numa_masks_clear(unsigned int cpu)
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
