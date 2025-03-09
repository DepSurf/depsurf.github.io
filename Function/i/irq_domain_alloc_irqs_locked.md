# Function: <code>irq_domain_alloc_irqs_locked</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_locked(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_irqs_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580549872,
      "name": "irq_domain_alloc_irqs_locked",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1489",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549872,
      "name": "irq_domain_alloc_irqs_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 973
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
int irq_domain_alloc_irqs_locked(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_irqs_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623280,
      "name": "irq_domain_alloc_irqs_locked",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1468",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623280,
      "name": "irq_domain_alloc_irqs_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
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
int irq_domain_alloc_irqs_locked(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_irqs_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688224,
      "name": "irq_domain_alloc_irqs_locked",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1468",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688224,
      "name": "irq_domain_alloc_irqs_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int irq_domain_alloc_irqs_locked(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
