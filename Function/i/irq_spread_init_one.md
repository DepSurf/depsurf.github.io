# Function: <code>irq_spread_init_one</code>

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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579827151,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:7",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579827084,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:10",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579863113,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:11",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579896103,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:11",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579943142,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:11",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579981919,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:11",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580032177,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
void irq_spread_init_one(struct cpumask * irqmsk, struct cpumask * nmsk, unsigned int cpus_per_vec)
```

```json
{
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082016,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
      "addr": 18446744071580082016,
      "name": "irq_spread_init_one",
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
void irq_spread_init_one(struct cpumask * irqmsk, struct cpumask * nmsk, unsigned int cpus_per_vec)
```

```json
{
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064592,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
      "addr": 18446744071580064592,
      "name": "irq_spread_init_one",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void irq_spread_init_one(struct cpumask * irqmsk, struct cpumask * nmsk, unsigned int cpus_per_vec)
```

```json
{
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065248,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
      "addr": 18446744071580065248,
      "name": "irq_spread_init_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void irq_spread_init_one(struct cpumask * irqmsk, struct cpumask * nmsk, unsigned int cpus_per_vec)
```

```json
{
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580198672,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
      "addr": 18446744071580198672,
      "name": "irq_spread_init_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void irq_spread_init_one(struct cpumask * irqmsk, struct cpumask * nmsk, unsigned int cpus_per_vec)
```

```json
{
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351376,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
      "addr": 18446744071580351376,
      "name": "irq_spread_init_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void irq_spread_init_one(struct cpumask * irqmsk, struct cpumask * nmsk, unsigned int cpus_per_vec)
```

```json
{
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573632,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
      "addr": 18446744071580573632,
      "name": "irq_spread_init_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491236948,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225250012,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284136852,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271767158,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580000913,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579939585,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579992449,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
  "name": "irq_spread_init_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580039185,
      "name": "irq_spread_init_one",
      "external": false,
      "loc": "kernel/irq/affinity.c:12",
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
void irq_spread_init_one(struct cpumask * irqmsk, struct cpumask * nmsk, unsigned int cpus_per_vec)
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
void irq_spread_init_one(struct cpumask * irqmsk, struct cpumask * nmsk, unsigned int cpus_per_vec)
```
</details>
</li>
</ul>
