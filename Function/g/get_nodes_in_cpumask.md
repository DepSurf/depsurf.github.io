# Function: <code>get_nodes_in_cpumask</code>

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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579826582,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:38",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579826506,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:81",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579862321,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:82",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579895636,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:82",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579942681,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:82",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579981436,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:82",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580031099,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
int get_nodes_in_cpumask(cpumask_var_t * node_to_cpumask, const struct cpumask * mask, nodemask_t * nodemsk)
```

```json
{
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082176,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082176,
      "name": "get_nodes_in_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int get_nodes_in_cpumask(cpumask_var_t * node_to_cpumask, const struct cpumask * mask, nodemask_t * nodemsk)
```

```json
{
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064752,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064752,
      "name": "get_nodes_in_cpumask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580065560,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580199032,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580352159,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580574463,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588179250,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "lib/group_cpus.c:85",
      "file": "lib/group_cpus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588470098,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "lib/group_cpus.c:85",
      "file": "lib/group_cpus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491236192,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225249464,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284135904,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271767046,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579999835,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579938507,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579991371,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
  "name": "get_nodes_in_cpumask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580038107,
      "name": "get_nodes_in_cpumask",
      "external": false,
      "loc": "kernel/irq/affinity.c:83",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
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
int get_nodes_in_cpumask(cpumask_var_t * node_to_cpumask, const struct cpumask * mask, nodemask_t * nodemsk)
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
int get_nodes_in_cpumask(cpumask_var_t * node_to_cpumask, const struct cpumask * mask, nodemask_t * nodemsk)
```
</details>
</li>
</ul>
