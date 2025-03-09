# Function: <code>build_group_from_child_sched_domain</code>

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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579683368,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:656",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579712224,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:657",
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579744145,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:649",
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579784076,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:848",
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579808553,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579856073,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
struct sched_group * build_group_from_child_sched_domain(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898672,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:875",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898672,
      "name": "build_group_from_child_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
struct sched_group * build_group_from_child_sched_domain(struct sched_domain * sd, int cpu)
```

```json
{
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893392,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:936",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893392,
      "name": "build_group_from_child_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579902742,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:907",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580020182,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:919",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580173671,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:935",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580357580,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:935",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580425161,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:942",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580484761,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:957",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491052780,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225057872,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283929944,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271651086,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579828425,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579763001,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579816441,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
  "name": "build_group_from_child_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579861561,
      "name": "build_group_from_child_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:877",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sched_group * build_group_from_child_sched_domain(struct sched_domain * sd, int cpu)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct sched_group * build_group_from_child_sched_domain(struct sched_domain * sd, int cpu)
```
</details>
</li>
</ul>
