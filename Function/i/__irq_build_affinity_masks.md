# Function: <code>__irq_build_affinity_masks</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579942512,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:97",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942512,
      "name": "__irq_build_affinity_masks.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981280,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:97",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981280,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1110
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030944,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030944,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1637
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082384,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082384,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064960,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064960,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065408,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065408,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580198880,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198880,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351984,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351984,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580574288,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574288,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491236008,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491236008,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1500
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225249352,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225249352,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284135680,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284135680,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271766956,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271766956,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999680,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999680,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1637
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938352,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938352,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1637
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991216,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991216,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1637
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
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```

```json
{
  "name": "__irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037952,
      "name": "__irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:247",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037952,
      "name": "__irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1637
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int __irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, cpumask_var_t * node_to_cpumask, const struct cpumask * cpu_mask, struct cpumask * nmsk, struct irq_affinity_desc * masks)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
