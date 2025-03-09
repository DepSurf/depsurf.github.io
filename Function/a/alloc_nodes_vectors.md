# Function: <code>alloc_nodes_vectors</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580031544,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, const nodemask_t nodemsk, struct cpumask * nmsk, struct node_vectors * node_vectors)
```

```json
{
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081632,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
      "addr": 18446744071580081632,
      "name": "alloc_nodes_vectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, const nodemask_t nodemsk, struct cpumask * nmsk, struct node_vectors * node_vectors)
```

```json
{
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064208,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
      "addr": 18446744071580064208,
      "name": "alloc_nodes_vectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, const nodemask_t nodemsk, struct cpumask * nmsk, struct node_vectors * node_vectors)
```

```json
{
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064864,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
      "addr": 18446744071580064864,
      "name": "alloc_nodes_vectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, const nodemask_t nodemsk, struct cpumask * nmsk, struct node_vectors * node_vectors)
```

```json
{
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580198288,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
      "addr": 18446744071580198288,
      "name": "alloc_nodes_vectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, const nodemask_t nodemsk, struct cpumask * nmsk, struct node_vectors * node_vectors)
```

```json
{
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351584,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
      "addr": 18446744071580351584,
      "name": "alloc_nodes_vectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, const nodemask_t nodemsk, struct cpumask * nmsk, struct node_vectors * node_vectors)
```

```json
{
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573888,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
      "addr": 18446744071580573888,
      "name": "alloc_nodes_vectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491236404,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225249532,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284136252,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271767110,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580000280,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579938952,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579991816,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
  "name": "alloc_nodes_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580038552,
      "name": "alloc_nodes_vectors",
      "external": false,
      "loc": "kernel/irq/affinity.c:128",
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
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, const nodemask_t nodemsk, struct cpumask * nmsk, struct node_vectors * node_vectors)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void alloc_nodes_vectors(unsigned int numvecs, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, const nodemask_t nodemsk, struct cpumask * nmsk, struct node_vectors * node_vectors)
```
</details>
</li>
</ul>
