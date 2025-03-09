# Function: <code>build_sched_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sched_domain * build_sched_domain(struct sched_domain_topology_level * tl, const struct cpumask * cpu_map, struct sched_domain_attr * attr, struct sched_domain * child, int cpu)
```

```json
{
  "name": "build_sched_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561520,
      "name": "build_sched_domain",
      "external": true,
      "loc": "kernel/sched/core.c:6930",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561520,
      "name": "build_sched_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
struct sched_domain * build_sched_domain(struct sched_domain_topology_level * tl, const struct cpumask * cpu_map, struct sched_domain_attr * attr, struct sched_domain * child, int cpu)
```

```json
{
  "name": "build_sched_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571776,
      "name": "build_sched_domain",
      "external": true,
      "loc": "kernel/sched/core.c:6865",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571776,
      "name": "build_sched_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sched_domain * build_sched_domain(struct sched_domain_topology_level * tl, const struct cpumask * cpu_map, struct sched_domain_attr * attr, struct sched_domain * child, int cpu)
```

```json
{
  "name": "build_sched_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597072,
      "name": "build_sched_domain",
      "external": true,
      "loc": "kernel/sched/core.c:6978",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597072,
      "name": "build_sched_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sched_domain * build_sched_domain(struct sched_domain_topology_level * tl, const struct cpumask * cpu_map, struct sched_domain_attr * attr, struct sched_domain * child, int cpu)
```

```json
{
  "name": "build_sched_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681344,
      "name": "build_sched_domain",
      "external": true,
      "loc": "kernel/sched/topology.c:1598",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681344,
      "name": "build_sched_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579710717,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1613",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579742653,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1608",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579782607,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1809",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579811187,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1834",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579859249,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579901703,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1840",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579896572,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1899",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579905098,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1927",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580022771,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:2121",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580194806,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:2177",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580385691,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:2177",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580454466,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:2277",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580514103,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:2312",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491056360,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225061152,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283934336,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271649828,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579831601,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579766177,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579819617,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
  "name": "build_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579864737,
      "name": "build_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:1855",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct sched_domain * build_sched_domain(struct sched_domain_topology_level * tl, const struct cpumask * cpu_map, struct sched_domain_attr * attr, struct sched_domain * child, int cpu)
```
</details>
</li>
</ul>
