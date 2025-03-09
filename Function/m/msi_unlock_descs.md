# Function: <code>msi_unlock_descs</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void msi_unlock_descs(struct device * dev)
```

```json
{
  "name": "msi_unlock_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580351173,
      "name": "msi_unlock_descs",
      "external": true,
      "loc": "kernel/irq/msi.c:236",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_free_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_get_virq"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344800,
      "name": "msi_unlock_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void msi_unlock_descs(struct device * dev)
```

```json
{
  "name": "msi_unlock_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580573347,
      "name": "msi_unlock_descs",
      "external": true,
      "loc": "kernel/irq/msi.c:342",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_free_irqs_all",
        "kernel/irq/msi.c:msi_domain_free_irqs_range",
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:msi_domain_alloc_irqs_range",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_match_device_irq_domain",
        "kernel/irq/msi.c:msi_remove_device_irq_domain",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "kernel/irq/msi.c:msi_domain_get_virq"
      ],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580563168,
      "name": "msi_unlock_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void msi_unlock_descs(struct device * dev)
```

```json
{
  "name": "msi_unlock_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580647961,
      "name": "msi_unlock_descs",
      "external": true,
      "loc": "kernel/irq/msi.c:342",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_free_irqs_all",
        "kernel/irq/msi.c:msi_domain_free_irqs_range",
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:msi_domain_alloc_irqs_range",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_match_device_irq_domain",
        "kernel/irq/msi.c:msi_remove_device_irq_domain",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "kernel/irq/msi.c:msi_domain_get_virq"
      ],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636592,
      "name": "msi_unlock_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void msi_unlock_descs(struct device * dev)
```

```json
{
  "name": "msi_unlock_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580713177,
      "name": "msi_unlock_descs",
      "external": true,
      "loc": "kernel/irq/msi.c:342",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_free_irqs_all",
        "kernel/irq/msi.c:msi_domain_free_irqs_range",
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:msi_domain_alloc_irqs_range",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_match_device_irq_domain",
        "kernel/irq/msi.c:msi_remove_device_irq_domain",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "kernel/irq/msi.c:msi_create_device_irq_domain",
        "kernel/irq/msi.c:msi_domain_get_virq"
      ],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701744,
      "name": "msi_unlock_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void msi_unlock_descs(struct device * dev)
```
</details>
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
