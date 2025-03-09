# Function: <code>msi_domain_first_desc</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct msi_desc * msi_domain_first_desc(struct device * dev, unsigned int domid, enum msi_desc_filter filter)
```

```json
{
  "name": "msi_domain_first_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580568558,
      "name": "msi_domain_first_desc",
      "external": true,
      "loc": "kernel/irq/msi.c:376",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:msi_verify_entries",
        "arch/x86/pci/xen.c:xen_teardown_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562800,
      "name": "msi_domain_first_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct msi_desc * msi_domain_first_desc(struct device * dev, unsigned int domid, enum msi_desc_filter filter)
```

```json
{
  "name": "msi_domain_first_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580642077,
      "name": "msi_domain_first_desc",
      "external": true,
      "loc": "kernel/irq/msi.c:376",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_device_destroy_sysfs",
        "kernel/irq/msi.c:msi_device_populate_sysfs"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:msi_verify_entries",
        "arch/x86/pci/xen.c:xen_teardown_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636224,
      "name": "msi_domain_first_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct msi_desc * msi_domain_first_desc(struct device * dev, unsigned int domid, enum msi_desc_filter filter)
```

```json
{
  "name": "msi_domain_first_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580707311,
      "name": "msi_domain_first_desc",
      "external": true,
      "loc": "kernel/irq/msi.c:376",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_device_destroy_sysfs",
        "kernel/irq/msi.c:msi_device_populate_sysfs"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:msi_verify_entries",
        "arch/x86/pci/xen.c:xen_teardown_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701376,
      "name": "msi_domain_first_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct msi_desc * msi_domain_first_desc(struct device * dev, unsigned int domid, enum msi_desc_filter filter)
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
