# Function: <code>pci_msi_domain_alloc_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_msi_domain_alloc_irqs(struct irq_domain * domain, struct pci_dev * dev, int nvec, int type)
```

```json
{
  "name": "pci_msi_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583383506,
      "name": "pci_msi_domain_alloc_irqs",
      "external": true,
      "loc": "drivers/pci/msi.c:1303",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_setup_msi_irqs"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388576,
      "name": "pci_msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_msi_domain_alloc_irqs(struct irq_domain * domain, struct pci_dev * dev, int nvec, int type)
```

```json
{
  "name": "pci_msi_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583697138,
      "name": "pci_msi_domain_alloc_irqs",
      "external": true,
      "loc": "drivers/pci/msi.c:1438",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_setup_msi_irqs"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703008,
      "name": "pci_msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_msi_domain_alloc_irqs(struct irq_domain * domain, struct pci_dev * dev, int nvec, int type)
```

```json
{
  "name": "pci_msi_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583835522,
      "name": "pci_msi_domain_alloc_irqs",
      "external": true,
      "loc": "drivers/pci/msi.c:1504",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_setup_msi_irqs"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841328,
      "name": "pci_msi_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int pci_msi_domain_alloc_irqs(struct irq_domain * domain, struct pci_dev * dev, int nvec, int type)
```
</details>
</li>
</ul>
