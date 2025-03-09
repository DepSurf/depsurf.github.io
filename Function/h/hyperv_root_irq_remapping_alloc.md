# Function: <code>hyperv_root_irq_remapping_alloc</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "hyperv_root_irq_remapping_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586859200,
      "name": "hyperv_root_irq_remapping_alloc",
      "external": false,
      "loc": "drivers/iommu/hyperv-iommu.c:269",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859200,
      "name": "hyperv_root_irq_remapping_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "hyperv_root_irq_remapping_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587422416,
      "name": "hyperv_root_irq_remapping_alloc",
      "external": false,
      "loc": "drivers/iommu/hyperv-iommu.c:269",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587422416,
      "name": "hyperv_root_irq_remapping_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int hyperv_root_irq_remapping_alloc(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "hyperv_root_irq_remapping_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588736144,
      "name": "hyperv_root_irq_remapping_alloc",
      "external": false,
      "loc": "drivers/iommu/hyperv-iommu.c:269",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588736144,
      "name": "hyperv_root_irq_remapping_alloc",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "hyperv_root_irq_remapping_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590221440,
      "name": "hyperv_root_irq_remapping_alloc",
      "external": false,
      "loc": "drivers/iommu/hyperv-iommu.c:272",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590221440,
      "name": "hyperv_root_irq_remapping_alloc",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "hyperv_root_irq_remapping_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590541312,
      "name": "hyperv_root_irq_remapping_alloc",
      "external": false,
      "loc": "drivers/iommu/hyperv-iommu.c:272",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590541312,
      "name": "hyperv_root_irq_remapping_alloc",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "hyperv_root_irq_remapping_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590897296,
      "name": "hyperv_root_irq_remapping_alloc",
      "external": false,
      "loc": "drivers/iommu/hyperv-iommu.c:272",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590897296,
      "name": "hyperv_root_irq_remapping_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs, void * arg)
```
</details>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
