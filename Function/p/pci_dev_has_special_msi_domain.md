# Function: <code>pci_dev_has_special_msi_domain</code>

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
bool pci_dev_has_special_msi_domain(struct pci_dev * pdev)
```

```json
{
  "name": "pci_dev_has_special_msi_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585525376,
      "name": "pci_dev_has_special_msi_domain",
      "external": true,
      "loc": "drivers/pci/msi.c:1589",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585525376,
      "name": "pci_dev_has_special_msi_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool pci_dev_has_special_msi_domain(struct pci_dev * pdev)
```

```json
{
  "name": "pci_dev_has_special_msi_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585403760,
      "name": "pci_dev_has_special_msi_domain",
      "external": true,
      "loc": "drivers/pci/msi.c:1595",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585403760,
      "name": "pci_dev_has_special_msi_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool pci_dev_has_special_msi_domain(struct pci_dev * pdev)
```

```json
{
  "name": "pci_dev_has_special_msi_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585865584,
      "name": "pci_dev_has_special_msi_domain",
      "external": true,
      "loc": "drivers/pci/msi.c:1513",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585865584,
      "name": "pci_dev_has_special_msi_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool pci_dev_has_special_msi_domain(struct pci_dev * pdev)
```

```json
{
  "name": "pci_dev_has_special_msi_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587060032,
      "name": "pci_dev_has_special_msi_domain",
      "external": true,
      "loc": "drivers/pci/msi/irqdomain.c:269",
      "file": "drivers/pci/msi/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060032,
      "name": "pci_dev_has_special_msi_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool pci_dev_has_special_msi_domain(struct pci_dev * pdev)
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool pci_dev_has_special_msi_domain(struct pci_dev * pdev)
```
</details>
</li>
</ul>
