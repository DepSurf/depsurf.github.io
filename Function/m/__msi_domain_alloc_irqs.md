# Function: <code>__msi_domain_alloc_irqs</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __msi_domain_alloc_irqs(struct irq_domain * domain, struct device * dev, int nvec)
```

```json
{
  "name": "__msi_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062784,
      "name": "__msi_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/msi.c:398",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062784,
      "name": "__msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
int __msi_domain_alloc_irqs(struct irq_domain * domain, struct device * dev, int nvec)
```

```json
{
  "name": "__msi_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063520,
      "name": "__msi_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/msi.c:398",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063520,
      "name": "__msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int __msi_domain_alloc_irqs(struct irq_domain * domain, struct device * dev, int nvec)
```

```json
{
  "name": "__msi_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580196944,
      "name": "__msi_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/msi.c:538",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196944,
      "name": "__msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
int __msi_domain_alloc_irqs(struct irq_domain * domain, struct device * dev, int nvec)
```

```json
{
  "name": "__msi_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580349216,
      "name": "__msi_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/msi.c:853",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349216,
      "name": "__msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
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
int __msi_domain_alloc_irqs(struct device * dev, struct irq_domain * domain, struct msi_ctrl * ctrl)
```

```json
{
  "name": "__msi_domain_alloc_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567664,
      "name": "__msi_domain_alloc_irqs",
      "external": false,
      "loc": "kernel/irq/msi.c:1253",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:__msi_domain_alloc_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567664,
      "name": "__msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
int __msi_domain_alloc_irqs(struct device * dev, struct irq_domain * domain, struct msi_ctrl * ctrl)
```

```json
{
  "name": "__msi_domain_alloc_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641184,
      "name": "__msi_domain_alloc_irqs",
      "external": false,
      "loc": "kernel/irq/msi.c:1250",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:__msi_domain_alloc_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641184,
      "name": "__msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1183
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
int __msi_domain_alloc_irqs(struct device * dev, struct irq_domain * domain, struct msi_ctrl * ctrl)
```

```json
{
  "name": "__msi_domain_alloc_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580706448,
      "name": "__msi_domain_alloc_irqs",
      "external": false,
      "loc": "kernel/irq/msi.c:1247",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:__msi_domain_alloc_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706448,
      "name": "__msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1125
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __msi_domain_alloc_irqs(struct irq_domain * domain, struct device * dev, int nvec)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct msi_ctrl * ctrl</code>
</li>
<li>
<b>Param removed. </b>
<code>int nvec</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, dev, nvec</code> ➡️ <code>dev, domain, ctrl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
