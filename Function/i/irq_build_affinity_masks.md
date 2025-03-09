# Function: <code>irq_build_affinity_masks</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579895456,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:97",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895456,
      "name": "irq_build_affinity_masks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579944076,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:176",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579982663,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:173",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580032855,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083216,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083216,
      "name": "irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065792,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065792,
      "name": "irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066432,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066432,
      "name": "irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199904,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199904,
      "name": "irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580353072,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:339",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353072,
      "name": "irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580575376,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:339",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575376,
      "name": "irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491237804,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225250756,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284137664,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284137664,
      "name": "irq_build_affinity_masks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271767860,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580001591,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579940263,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579993127,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_build_affinity_masks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580039863,
      "name": "irq_build_affinity_masks",
      "external": false,
      "loc": "kernel/irq/affinity.c:338",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
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
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc * masks)
```
</details>
</li>
</ul>
