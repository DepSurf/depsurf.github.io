# Function: <code>msi_domain_alloc_irq_at</code>

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
struct msi_map msi_domain_alloc_irq_at(struct device * dev, unsigned int domid, unsigned int index, const struct irq_affinity_desc * affdesc, union msi_instance_cookie * icookie)
```

```json
{
  "name": "msi_domain_alloc_irq_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572288,
      "name": "msi_domain_alloc_irq_at",
      "external": true,
      "loc": "kernel/irq/msi.c:1472",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_ims_alloc_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572288,
      "name": "msi_domain_alloc_irq_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
struct msi_map msi_domain_alloc_irq_at(struct device * dev, unsigned int domid, unsigned int index, const struct irq_affinity_desc * affdesc, union msi_instance_cookie * icookie)
```

```json
{
  "name": "msi_domain_alloc_irq_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646688,
      "name": "msi_domain_alloc_irq_at",
      "external": true,
      "loc": "kernel/irq/msi.c:1469",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_ims_alloc_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646688,
      "name": "msi_domain_alloc_irq_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
struct msi_map msi_domain_alloc_irq_at(struct device * dev, unsigned int domid, unsigned int index, const struct irq_affinity_desc * affdesc, union msi_instance_cookie * icookie)
```

```json
{
  "name": "msi_domain_alloc_irq_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580711904,
      "name": "msi_domain_alloc_irq_at",
      "external": true,
      "loc": "kernel/irq/msi.c:1459",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_ims_alloc_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580711904,
      "name": "msi_domain_alloc_irq_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
struct msi_map msi_domain_alloc_irq_at(struct device * dev, unsigned int domid, unsigned int index, const struct irq_affinity_desc * affdesc, union msi_instance_cookie * icookie)
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
