# Function: <code>build_balance_mask</code>

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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579683821,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:619",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579712359,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:620",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579744316,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:612",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579784247,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:811",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579808721,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579856241,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
void build_balance_mask(struct sched_domain * sd, struct sched_group * sg, struct cpumask * mask)
```

```json
{
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898832,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:838",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:init_overlap_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898832,
      "name": "build_balance_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void build_balance_mask(struct sched_domain * sd, struct sched_group * sg, struct cpumask * mask)
```

```json
{
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893552,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:899",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:init_overlap_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893552,
      "name": "build_balance_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579902902,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:870",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580020366,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:882",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580173869,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:898",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580357768,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:898",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580425394,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:905",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580484998,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:920",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491052924,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225057976,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283930096,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271651260,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579828593,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579763169,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579816609,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
  "name": "build_balance_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579861729,
      "name": "build_balance_mask",
      "external": false,
      "loc": "kernel/sched/topology.c:840",
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
void build_balance_mask(struct sched_domain * sd, struct sched_group * sg, struct cpumask * mask)
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
void build_balance_mask(struct sched_domain * sd, struct sched_group * sg, struct cpumask * mask)
```
</details>
</li>
</ul>
