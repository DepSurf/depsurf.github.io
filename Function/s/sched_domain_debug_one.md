# Function: <code>sched_domain_debug_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579534302,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/core.c:5662",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579545479,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/core.c:5623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579570714,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/core.c:5657",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579677935,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:32",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579708574,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:32",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579749397,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579789429,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816928,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816928,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579865240,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579906054,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906054,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
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
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591282801,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:34",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282801,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 931
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
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591225969,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:34",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591225969,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
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
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592112172,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:34",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592112172,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
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
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593883902,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:33",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593883902,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1001
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
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580354416,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:33",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354416,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1302
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
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580422544,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:35",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422544,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1302
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
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480768,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:35",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480768,
      "name": "sched_domain_debug_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1302
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491063788,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491063788,
      "name": "sched_domain_debug_one.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225065544,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225065544,
      "name": "sched_domain_debug_one.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283942688,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283942688,
      "name": "sched_domain_debug_one.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271654716,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271654716,
      "name": "sched_domain_debug_one.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579837592,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579772168,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579825608,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
  "name": "sched_domain_debug_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579870744,
      "name": "sched_domain_debug_one",
      "external": false,
      "loc": "kernel/sched/topology.c:28",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int sched_domain_debug_one(struct sched_domain * sd, int cpu, int level, struct cpumask * groupmask)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
