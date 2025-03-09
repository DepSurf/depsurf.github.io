# Function: <code>pci_real_dma_dev</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
```

```json
{
  "name": "pci_real_dma_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585318240,
      "name": "pci_real_dma_dev",
      "external": true,
      "loc": "drivers/pci/pci.c:6114",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139776,
      "name": "pci_real_dma_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
```

```json
{
  "name": "pci_real_dma_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585473216,
      "name": "pci_real_dma_dev",
      "external": true,
      "loc": "drivers/pci/pci.c:6188",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224016,
      "name": "pci_real_dma_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
```

```json
{
  "name": "pci_real_dma_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585353072,
      "name": "pci_real_dma_dev",
      "external": true,
      "loc": "drivers/pci/pci.c:6237",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173264,
      "name": "pci_real_dma_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
```

```json
{
  "name": "pci_real_dma_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585812064,
      "name": "pci_real_dma_dev",
      "external": true,
      "loc": "drivers/pci/pci.c:6427",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592026784,
      "name": "pci_real_dma_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
```

```json
{
  "name": "pci_real_dma_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587001168,
      "name": "pci_real_dma_dev",
      "external": true,
      "loc": "drivers/pci/pci.c:6524",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:domain_add_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793824,
      "name": "pci_real_dma_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
```

```json
{
  "name": "pci_real_dma_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588170016,
      "name": "pci_real_dma_dev",
      "external": true,
      "loc": "drivers/pci/pci.c:6473",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595736992,
      "name": "pci_real_dma_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
```

```json
{
  "name": "pci_real_dma_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588446048,
      "name": "pci_real_dma_dev",
      "external": true,
      "loc": "drivers/pci/pci.c:6595",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596262976,
      "name": "pci_real_dma_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
```

```json
{
  "name": "pci_real_dma_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588742912,
      "name": "pci_real_dma_dev",
      "external": true,
      "loc": "drivers/pci/pci.c:6739",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/pci.c:pci_devs_are_dma_aliases",
        "drivers/pci/search.c:pci_for_each_dma_alias",
        "drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/iommu.c:device_lookup_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597145632,
      "name": "pci_real_dma_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct pci_dev * pci_real_dma_dev(struct pci_dev * dev)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
